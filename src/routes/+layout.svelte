<div id='container'>
<link rel="stylesheet" href="src/assets/main.css" />	
    <header class="header">
     <h1><a href="/">태성고등학교 입시포털</a></h1>
     <div id="nav">
            <ul>
              <li><a href="/line">생기부 작성 요령</a></li>
              <li><a href="/gradecut">등급컷 대학 라인업</a></li>
              <li><a href="/subject">선택과목 가이드</a></li>
              <li><a href="/test">모의고사 기출 자료실</a></li>
             <li><a href="/graduate">모교 진학 통계</a></li>
          </ul>
      </div>
    </header>
    <main>
        <div class='contents'>
            <slot></slot>
        </div>
    </main>
    <footer>태성고등학교 IF 동아리</footer>
</div>