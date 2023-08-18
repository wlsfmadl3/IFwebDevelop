<script>

	import { buildErrorMessage } from "vite";

</script>
<div id='container'>
<link rel="stylesheet" href="src/assets/main.css" />	
<link rel="stylesheet" href="src/assets/line.css" />	

<header class="header">
    <h1 class="round shadow1"style="color: white; background-color: #6666FF; width: 470px;"><a href="/">태성고등학교 입시포털</a></h1>
    <style>
     .shadow1{
         color: blue;
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
                <li><a href="/1class">1등급</a></li>
                <li><a href="/2class">2등급</a></li>
                <li><a href="/3class">3등급</a></li>
                <li><a href="/4class">4등급</a></li>
                <li><a href="/5class">5등급</a></li>
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