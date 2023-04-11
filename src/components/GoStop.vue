<template>
    <div class="desc">
        <!-- 배열에 있는 데이터를 map 돌리기 vue는 v-for로 한다 -->
        <!-- https://simplevue.gitbook.io/intro/04.-loop-condition 참고 -->
        <span v-for="itm in num" :key="itm">{{ itm.name }}</span>
    </div>
</template>

<script>
export default {
    name:"GoStop",
    data() {
        return {
            num: [
                {name: '고길동', age:47},
                {name: '둘리', age:8},
                {name: '희동이', age:5},
            ],
        };
    },
};
</script>

<!-- scoped는 이름이 랜덤으로 생성되어 스타일이 오염되지 않는다 (class 이름 중복 방지) -->
<style lang="scss" scoped>
.desc {
    color: tomato;
    span {
        display: block;
        font-size: 25px;
    }
}
</style>
