<p align="center"><img src="https://user-images.githubusercontent.com/67620791/86084688-7103d400-bad8-11ea-8807-b47327edf1d3.png"></p>

#

~~~bash
GUI(Graphical User Interface): 초보자가 명령이나 작업을 이해하기 쉽도록 도와주는 도구
~~~
'Git GUI Client'는 Git을 쉽게 사용할 수 있도록 도와주는 역할을 하는 프로그램으로,   
없어도 Git은 충분히 사용하실 수 있습니다.      
클라이언트를 사용하고 싶다면 자신에게 맞는 프로그램을  _선택적으로 설치_ 해주세요.   
(각 클라이언트의 로고를 클릭하시면 다운로드 페이지로 넘어가실 수 있습니다.)


### 1. Cross-platform Git Clients

<!-- GitKraken -->
<a href="https://www.gitkraken.com/"><img src="https://user-images.githubusercontent.com/67620791/86193781-cb0fa280-bb87-11ea-8adb-a3e064a229fd.png" width="100px"></a>

<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>자주 사용되는 도구와 정보에 대한 버튼 有</li>
                <li>공동 작업자와의 쉬운 commit</li>
                <li>repository에 있는 모든 pull 요청을 볼 수 있음</li>
                <li>pull 요청에 대한 상태 확인 가능</li>
                <li>구문 강조</li>
                <li>간단한 실행 취소/다시 실행 버튼</li>
                <li>
                    응용 프로그램 내에서 병합 충돌을 해결 가능<br>
                   (이 기능은 무료 버전에서 사용할 수 있지만<br>
                    병합 충돌 출력 편집기는 유료 버전)
                </li>
            </td>
            <td>
                <li>Linux 지원X</li>
                <li>모든 Git 기능 사용 X</li>
                <li>한 번에 여러 branch나 여러 태그에 걸쳐서 커밋 X</li>
                <li>commit history에 대한 안전 보장 X</li>
                <li>일부만 branching 또는 clone X</li>
                <li>190619 업데이트 이후 개인 저장소 무료 사용 X</li>
                <li>오류가 발생에 대한 정보 X</li>
                <li>
                    commit한 사람에 대한 정보 X<br>
                   (특정 commit을 클릭하거나 commiter 색상 암기)
                </li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //GitKraken -->

<!-- SmartGit -->
<a href="https://www.syntevo.com/smartgit/"><img src="https://user-images.githubusercontent.com/67620791/86193784-ccd96600-bb87-11ea-8923-f5439d8297e0.png" width="100px"></a>

<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>Windows와 Mac, Linux 지원</li>
                <li>비상업적 용도, 무료</li>
                <li>처음 사용할 때 디스크의 repo를 자동 감지</li>
                <li>많이 사용되는 도구 및 정보 항상 상단 표시</li>
                <li>필요에 따라 숨기고 재정렬이 가능한 인터페이스</li>
                <li>특정 기준(e.g. files/branches/branch graph 등)에 대한 필터링이 가능</li>
                <li>여러 repo를 포함하는 repo 그룹 생성 가능</li>
                <li>Git flow 기능 지원</li>
                <li>Git/Mercurial에서 직접 제공하지 않는 고급 작업 수행</li>
                <li>사용자 정의 가능한 색상으로 구문 비교 가능</li>
            </td>
            <td>
                <li>상업적 이용시 비용 발생</li>
                <li>다중 사용자 라이센스 X</li>
                <li>긴 줄을 변경하면 diff 표시 탐색에 어려움</li>
                <li>한 번에 여러 branch나 여러 태그에 걸쳐서 커밋 X</li>
                <li>일부만 branching 또는 clone X</li>
                <li>글꼴 크기변경 X</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //SmartGit -->

<!-- Git Cola -->
<a href="https://git-cola.github.io/index.html/"><img src="https://user-images.githubusercontent.com/67620791/86193788-ce0a9300-bb87-11ea-8beb-182d9ad68531.png" width="100px">
    
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>Python을 사용하여 개발</li>
                <li>필요에 따라 숨기고 재정렬이 가능한 인터페이스</li>
                <li>Git 작업을 위한 키보드 단축키 목록을 제공</li>
                <li>commit 및 분기를위한 시각화 프로그램 Git-Dag 有</li>
                <li>창 레이아웃을 기억하여 다음에 시작했을 때 복원</li>
            </td>
            <td></td>
        </tr>
    </tbody>
</table>
<!-- //Git Cola -->

===

### 2. Git Clients for Windows

<!-- sourcetreeapp -->
<a href="https://www.sourcetreeapp.com/"><img src="https://user-images.githubusercontent.com/67620791/86194136-b1228f80-bb88-11ea-81dd-711bbed43d1b.png" width="300px"></a> 
                                                                                                                            
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>무료</li>
                <li>Git flow 기능 내장</li>
                <li>Windows/Mac 지원</li>
                <li>한눈에(시각적으로) 상태 확인 가능</li>
                <li>다음 행동을 알려주어 비전문가라도 쉽게 사용 가능</li>
                <li>branch(브랜치)를 그래프로 보면서 관리</li>
            </td>
            <td>
                <li>내부적으로 Git 커맨드라인을 사용하므로 <a href="https://gitforwindows.org/">msysgit</a> 필수 설치</li>
                <li>Linux 지원X</li>
                <li>한꺼번에 많은 파일을 올릴 때 에러 발생</li>
                <li>주기적인 사용자 인증</li>
                <li>Repository Clone 마다 주소값 복사+붙여넣기</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //sourcetreeapp -->

<!-- tortoisegit -->
<a href="https://tortoisegit.org/"><img src="https://user-images.githubusercontent.com/67620791/86194054-73256b80-bb88-11ea-9a77-05e56605b265.png" width="200px"></a>   
                                                                                                                            
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>Windows 탐색기에서 바로 액세스 할 수있는 명령으로, 사용하기 쉬움</li>
                <li>탐색기에 통합되어 Git작업을 위한 별도 프로그램을 띄울 필요X</li>
                <li>
                    아이콘 오버레이(Icon overlay) 기능<br>
                    (각 폴더 및 파일의 기존 아이콘 위에 Git의 상태를 알려주는<br> 
                    아이콘을 덧붙여 표시함으로서 별도의 명령을 사용하지 않고<br> 50
                    상태확인 가능)
                </li>
                <li>컨텍스트 메뉴를 활용하여 Git 명령어 이용</li>
                <li>TortoiseSVN 의 소스 기반으로, 기존 Tortoise 사용자에게 친숙한 UI</li>
                <li>키워드와 경로에 대한 메시지와 자동 완성을 기록하는 맞춤법 검사기 제공</li>
            </td>
            <td>
                <li>기능 및 안정성의 부족</li>
                <li>Mac 지원X</li>
                <li>추가되는 기능에 따란 설명서 부족</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //tortoisegit -->

===

### 3. Git Clients for Mac

<!-- Git Box -->
<a href="http://www.gitboxapp.com/"><img src="https://user-images.githubusercontent.com/67720048/86573190-fbec3f00-bfae-11ea-96b5-367273ac9f79.png" width="100px"></a>   
                                                                                                                            
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>Git 명령 추가 및 취소 용이</li>
                <li>개정 내역 검색 용이</li>
                <li>최신 commit을 자동으로 가져옴</li>
                <li>새로운 commit이 추가될 때마다 모든 하위 모듈에 자동 업데이트</li>
                <li>Xcode FileMerge , Kaleidoscope , Changes , DiffMerge 와 통합</li>
                <li>merge commit과 충돌을 피하면서 서버에서 새 commit 자동 검색 가능</li>
                <li>작성자 또는 설명별로 검색 가능</li>
            </td>
            <td>
                <li>Mac App Store에서 $ 14.99 의 라이센스로 제공<br>(학생 인 경우 학생 ID를 통해 50% 할인)</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //Git Box -->

<!-- Git-Xdev -->
<a href="https://rowanj.github.io/gitx/"><span style="font-size:11pt">Git-Xdev</span></a>   
                                                                                                                            
<table>
     <thead>        
        <tr>
            <th>장점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>소프트웨어 개발자를 위한 전문화</li>
                <li>대부분의 Git work-flows를 위한 모든 기능 O</li>
                <li>개정의 전체 tree 확인 O</li>
                <li>텍스트보기에서 파일 미리보기 O(QuickLook)</li>
                <li>트리에서 파일 drag O</li>
                <li>git rev-list의 모든 매개 변수 지원</li>
                <li>대규모 repository에서 우수한 성능</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //Git-Xdev -->
 
<!-- GitUp -->
<a href="https://gitup.co/"><img src="https://user-images.githubusercontent.com/67720048/86573186-fabb1200-bfae-11ea-9b54-7810c3e2c34a.png" width="100px"></a>   
                                                                                                                            
<table>
     <thead>        
        <tr>
            <th>장점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>
                    branche 및 commit을 실시간으로 볼 수 O<br>
                    → 명령을 실행할 때마다 새로운 노드 비주얼이 만들어지고<br> 그래프의 변경 사항을 신속하게 반영
                </li>
                <li>commit의 차이점과 충돌을 보여주는 바로 가기 키 제공</li>
                <li>
                    라이브 맵 기능 제공<br>
                    → 프로젝트를 새로 고치지 않고도 진행 상황 확인 O
                </li>
                <li>branch를 보고 명확하게 병합 가능</li>
                <li>처음 사용하는 이용자를 위해 배우고 실험 할 수 있는 안전한 환경 제공</li>
                <li>실행 취소 및 스냅 샷 기능으로 단계를 변경하고 기록</li>
                <li>1 초 이내에 40,000 개의 커밋 로드 O</li>
                <li>repository에서 commit, branch 및 tag 즉시 검색 O</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //GitUp -->

===

### 4. Git Clients for Linux

<!-- GitForce -->
<a href="https://git-scm.com/download"><img src="https://user-images.githubusercontent.com/67620791/86193789-ce0a9300-bb87-11ea-8334-d78923f02339.gif" width="100px"></a>
       
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>설치가 필요없는 단일 실행 파일</li>
                <li>local repository 쉽게 스캔</li>
                <li>다중 원격 저장소 지원</li>
                <li>SSH key 및 원격 관리 용이</li>
                <li>개정 내역, 숨김, 숨김 등을 나열</li>
                <li>통합 된 Git 명령 인터페이스</li>
            </td>
            <td>
                <li>가장 일반적인 Git 작업에만 적합, 자세한 상태정보 유지 X</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //GitForce -->

<!-- Gitg -->
<a href="https://wiki.gnome.org/Apps/Gitg"><img src="https://user-images.githubusercontent.com/67620791/86193790-cea32980-bb87-11ea-9efd-f4cb082e7b20.png" width="100px"></a>
                    
<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>매우 간소화 된 UI</li>
                <li>컴퓨터에 저장된 기존 Git 리포지토리를 열 수 O</li>
                <li>종합 repository 내역</li>
                <li>최근에 사용한 리포지토리 개요</li>
                <li>commit 및 변경 기록을 모두 저장</li>
                <li>commit 단계적 변경</li>
            </td>
            <td>OX
                <li>큰 파일은 느리게 로드되는 경향</li>
                <li>프로젝트 히스토리를 표시하지 X</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //Gitg -->

===

### 5. ETC
<!-- Github Desktop -->
<a href="https://desktop.github.com/"><img src="https://user-images.githubusercontent.com/67620791/86193792-cf3bc000-bb87-11ea-9615-886d7e765fce.png" width="100px"></a>

<table>
    <colgroup>
        <col style="width=50%">
        <col style="width=50%">
    </colgroup>
     <thead>        
        <tr>
            <th>장점</th>
            <th>단점</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <li>GitHub 팀이 구축한 공식 GitHub clients</li>
                <li>자주 사용되는 도구와 정보에 대한 버튼 有</li>
                <li>공동 작업자와의 쉬운 commit</li>
                <li>단순한 2개의 패널보기 사용</li>
                <li>GitHub에서 호스팅되는 모든 프로젝트에서<br>pull 요청을 forking and submitting O</li>
                <li>변경 사항을 독립적인 diff로 분리</li>
            </td>
            <td>
                <li>Linux 지원X</li>
                <li>복잡한 작업을 처리 X<br>(복잡한 git 명령을 실행하려면 콘솔에 입력)</li>
                <li>한 번에 여러 branch나 tag에 걸쳐서 커밋 X</li>
                <li>commit history에 대한 안전 보장 X</li>
                <li>파일이 많거나 1GB를 초과하는 프로젝트는<br>로드가 느림</li>
                <li>작업 실패시 설명이 부족</li>
                <li>부분 파일에 대한 commit X</li>
            </td>
        </tr>
    </tbody>
</table>
<!-- //Github Desktop -->

    
### Reference
+ 도리가이드 [https://dora-guide.com/git-gui-client/]
+ 지옥에서 온 Git(생활코딩) [https://opentutorials.org/module/3746]
+ slant [https://www.slant.co/topics/2089/versus/~smartgit_vs_fork_vs_visual-studio-code]
+ HOSTINGER [https://www.hostinger.com/tutorials/best-git-gui-clients/]

### Images Origin
+ 각 홈페이지(CC BY )

