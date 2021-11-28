<template>
    <article class="korea__article" >
        <div class="korea__banner">
            <img src="https://cache.wemixnetwork.com/wemix-event/newsis/collaboration.png" alt="" class="korea__banner-newsis-logo"> 
            <img src="https://cache.wemixnetwork.com/wemix-event/newsis/every-where-korea.png" alt="" class="korea__banner-title"> 
            <p>여러분이 있어 2021년 대한민국은 행복했습니다. 감사합니다.<br>
                창사 20주년을 맞은 공감언론 뉴시스입니다. 1년 365일, 24시간, 대한민국 모든 역사의 현장에는 뉴시스가 있습니다. </p> 
            <p>EVERYWHERE 대한민국 NFT를 소장해 보세요.<br>
                마음에 드는 NFT에 응모하고 한정판 NFT를 소장해 보세요. 각각의 EVERYWHERE 대한민국 NFT는 숨은 영웅들에게 특별 지급됩니다</p> 
            <p>판매 수익금은 뉴시스가 사회복지공동모금회에 전액 기부할 예정입니다.</p> 
            <p>* 사진을 클릭하시면 원본을 보실 수 있습니다.</p> 
            <div class="korea__banner-date">
                <ul>
                <li>이벤트 기간 : 2021년 11월 10일(수) ~ 11월 30일(화)</li> 
                <li>당첨자 발표 : 2021년 12월 6일(월)</li> 
                <li>당첨자 NFT 구매 일정 : 2021년 12월 9일(목) 부터</li>
                </ul>
            </div> 
            <div class="korea__banner-guide"></div>
        </div> 
        <Items />
    </article>
</template>

<script>
import Items from './Items.vue'

export default{
    components: {
        Items
    }
}
</script>