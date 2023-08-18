<script>

	import { buildErrorMessage } from "vite";

</script>
<div id='container'>
<link rel="stylesheet" href="src/assets/main.css" />	
<link rel="stylesheet" href="src/assets/line.css" />	
<link rel="stylesheet" href="src/assets/tables.css" />	

    <header class="header">
       <h1 class="round shadow1"style="color: white; background-color: #6666FF; width: 470px;"><a href="/">태성고등학교 입시포털</a></h1>
       <style>
        .shadow1{
            color: white;
            text-shadow: 7px -7px 20px #000; 

        }
        .round{
            border-bottom-right-radius: 20px;
            border-bottom-right-radius: 20px;
            border-top-left-radius: 20px;
            border-top-left-radius: 20px;
        }
       </style>
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