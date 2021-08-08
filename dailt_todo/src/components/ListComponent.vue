<template>
  <div id="list" style="height:900px">
      <div class="gap">
          <ul>
              <li><div>사이렌 오더 음료 기본 설정 변경 안내 (HOT → ICED) 공지사항 업데이트</div></li>
              <li><div>시스템 개선 및 점검 안내</div></li>
              <li><div>스타벅스 카드 이용약관 개정 안내</div></li>
              <li><div>어플리케이션 개선 및 점검 안내</div></li>
              <li><div>내부 주문 오류 개선 및 점검 안내</div></li>
              <li><div>SSG PAY 결제 서비스 일시 이용 중지 안내</div></li>
              <li><div>스타벅스 홈페이지/애플리케이션 일부 서비스 종료 안내</div></li>
              <li><div>스타벅스 Web/App 결제 수단 변경 안내</div></li>
              <li><div>설 연휴 스타벅스 딜리버스 운영 시간 안내</div></li>
              <li><div>스타벅스 카드 이용약관 개정 안내</div></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    #list .gap{padding: 15px 20px;}
    #list li{border-bottom: 1px solid #ccc;}
    #list li div{font-size: 14px;line-height: 30px;overflow: hidden;text-overflow: ellipsis;white-space: nowrap;background-color: #fff;text-indent: 20px;position: relative;z-index: 1;}
    #list li div::before{content:'';display: block;position: absolute;top: calc(50% - 3px);left:7px;width: 6px;height: 6px;background-color: #888;border-radius: 3px;z-index: 2;}
</style>
