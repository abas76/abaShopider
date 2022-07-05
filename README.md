# abaShopider
“온라인쇼핑몰 웹사이트 크롤링 엔진,프레임웍”
Online ShopingMall 구매내역, 찜(WishList)목록 Cralwing Engine


온라인쇼핑 구매목록, 찜목록을
일반적인 크롤링의 문제점은 수많은 쇼핑몰사이트들의 구조가 변경될 경우 이에 대응하기위한 운영 관리 리소스가 많이 들어갈수 있다는 문제점이 있는데 
이를 극복하기 위해 크롤링 엔진을 만들고 Json형태로 간단하게 구조를 정의하여 패턴화한 쇼핑몰사이트정보를 엔진이 자동으로 크롤링하여 
공수 최소화로 운영이 가능한 엔진입니다.
Site-Page–Element, Crawler, Site, CrawlerPool, SitePool등의 Component등의 구성으로 설계하였고 Selenium Chrome기반으로 개발하였으며 
대량 MultiThreading기반으로 개발되어 서버사양에 따라 수십개단위의 동시 Crawling이 가능합니다. 또한 쇼핑몰 페이지만이 아닌  일반적인 웹사이트에 대해 확장 가능하여 다른 분야로 적용도 생각해볼 수 있습니다.
현재 15개 국내외 사이트를 등록하였고 쇼핑몰별 구매내역 목록뿐만 아니라 찜목록(WishList)들도 등록하여 같이 수집하도록 개발되었고, 사이트는 간단히 추가 진행중 입니다. 
아마존,쿠팡,eBay,iHerb의 경우 IP Decial정책에 의해 이곳에서는 테스트는 불가할 수 있으니 참고해주세요.


# 20220705 현재 지원가능 쇼핑몰
 . 무신사, Gmarket, Auction, 11st, Naver, Coupang, SSG.com, 마켓컬리, 오늘의집, 아이디어스, 브랜디, 아마존, eBay, iHerb, ChainreactionCycles


# Test 방법
Test Page : http://223.130.163.73/shoppingMoa/admin/siteCrawlPage
쇼핑몰 선택후 id/pw 입력후 "크롤링" 버튼
현재 구매목록뿐만 아니라 위시리스트도 모두 Crawling 하여 속도가 좀 느릴수 있습니다.




![image](https://user-images.githubusercontent.com/24688298/177270430-469b72d2-ffa7-4dda-baac-b477703fc9b2.png)






# 문의사항 : abas76@gmail.com

