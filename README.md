##카카오톡 클론코딩 강의내용 정리

[#1] Introduction


[#2] Study html
<2.0> 
#Name of files and folders should be written in small letters.
#HTML files can be opened with any "browsers" 
#ctrl + r = f5
#HTML file을 오픈한 웹브라우저의 사이트 주소는 경로명과 동일

<2.1>&*<2.2>
#웹브라우저에서 열고 있는 파일이 현재 작업 중인 파일이 맞는지 확인할 것
#HTML tag(=text) 사이에 들어가는 게 content(내용, 지시사항)
#tag의 작성 순서는 <tag의 종류>tag의 내용(content)</tag의 종류>
#'/' is close flag of a tag
#VSC가 close tag 자동으로 추가해줌 
#'요소검사' views html code
#HTML tag vs not-HTML tag(what is different?)
#tag 엄청 많음(암기x)
#close tag 작성 안 하면 자동으로 전체를 tag로 인식

<2.3>
#HTML의 list : (1) ordered => "ol ag" /(2) unordered => "ul tag" (list를 생성하려면 "li tag" 추가)
#ctrl + d : 해당 단어와 같은 단어 모두 선택
#HTML code edtior로 "prettier" 추천

<2.4>&<2.5>
#title tag(=h[] tag)와 다르게 link tag(=a tag/anchor tag)는 attribute이 필요
#href = HTTP reference = hyperlink reference = attribute of "a tag"
#tag name과 attribute 사이 반드시 띄어쓰기
#target(속성) 기본값 : _self
#_blank도 사용가능한데 _self는 현재 탭에서, _blank는 새로운 탭에서 href가 실행됨
#tag마다 수많은 attributes
#img tag는 "self-closing tag"이기 때문에 /를 사용한 별도의 close tag가 없다 + text를 미포함하므로 content도 없다!
#img는 src attribute로 삽입
#온라인 이미지는 src에 경로를, local image는 반드시 "같은 폴더" 내에 위치한 이미지 파일과 "동일한" 파일명을.
#HTML 문서 작성 규칙(->home2.html): 
(1) HTML 문서는 반드시 <!DOCTYPE html>로 시작해야 한다. (브라우저에게 이것이 text가 아닌 html 파일임을 명시)
*이 코드는 닫아줄 필요가 없는 특수 케이스
(2) HTM tag를 열어서 그 안에 html code를 작성한다. (이 때 HTML의 구조를 반영하여 HEAD와 BODY를 나누어 작성한다.)
*HTML의 구조: HEAD + BODY
**HEAD : 웹사이트의 환경 설정(외부적으로 드러나지 X)
**BODY : 사용자에게 보여지는 부분

-> 이렇게 작성하면 head와 body로 정리됨

#HTML은 오류가 있더라도 실행에 문제가 없으면 이해한 결과를 출력하기 때문에 반드시 잘 살펴봐야 함.

<2.6>
#HEAD tag의 내용들은 보여지지 않는다!!!

#meta(부가 정보) tag : 브라우저가 사이트로부터 정보를 가져옴
#meta tag의 attributes = "content" && "name" && "charset"(text를 어떻게 그릴지 지시 - 글자 깨짐 방지)
#meta charset="utf-8"
#html의 "lang" attribute은 검색 엔진에게 브라우저가 사용 중인 언어에 대한 정보를 전달
#link tag : 탭에 아이콘 이미지를 추가하는 태그
#property tag의 og:image attribute은 카카오톡에 공유될 때 보여지는 이미지와 같은 화면을 구성
(og:title과 함께 사용/)

<2.7>
#검색 시 mdn 키워드를 추가하면 fireforks browser를 만든 회사에서 제공하는 js, css, html 관련 문서를 제공받을 수 있다.
#<p> tag for paragraph
#<abbr> tag for abbreviation
#<cite> tag for 기울임체
#