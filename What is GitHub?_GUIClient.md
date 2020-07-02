<p align="center"><img src="https://user-images.githubusercontent.com/67620791/86084688-7103d400-bad8-11ea-8807-b47327edf1d3.png"></p>

#

## Cross-platform Git GUI Client
GUI는 'Graphical User Interface'의 약자로,   
초보자가 명령이나 작업을 이해하기 쉽도록 프로젝트 히스토리를 시각화하여 도와주는 도구이다.   
즉, Git 명령어를 쉽게 사용할 수 있도록 도와주는 역할이기 때문에 _선택적으로 설치_ 하면 된다.   
아래는 Linux, Windows 또는 Mac 플랫폼에서 실행할 수있는 모든 기능을 갖춘 Git 클라이언트이다.

<table>
    <thead>        
        <tr>
            <th colspan="2">Client</th>
            <th colspan="2"></th>
        </tr>
    </thead>
    <tbody>
        <!-- SourceTree -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86194136-b1228f80-bb88-11ea-81dd-711bbed43d1b.png" width="300px"><br><br>
                <a href="https://git-scm.com/download">SourceTree</a>
            </th>
            <td>장점</td>
            <td>
                1. <strong>무료</strong><br>
                2. Git flow 기능을 내장하고 있다.<br>
                3. Windows와 Mac을 지원한다.<br>
                4. 한 눈에(시각적으로) 상태를 확인할 수 있으며, 다음 행동을 알려주어 비전문가라도 쉽게 사용 가능하다.
                5. 많은 branch(브랜치)를 그래프로 보면서 손쉽게 관리할 수 있다.
                6. branch를 나누어서 수정, 병합할 수 있다.
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. 내부적으로 Git 커맨드라인을 사용하므로 <a href="https://gitforwindows.org/">msysgit</a>을 설치해야 한다.<br>
                2. 아직 Linux는 지원하지 않는다<br>
                3. 한꺼번에 많은 파일을 올릴 때 에러가 발생한다.
                4. CLI의 모든 기능을 지원하지 않기 때문에 CLI로 하는 법을 필수로 익혀야 한다.
            </td>
        </tr>
        <!-- //SourceTree -->
        <!-- Tortoisegit -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86194054-73256b80-bb88-11ea-9a77-05e56605b265.png" width="70px"><br><br>
                <a href="https://tortoisegit.org/">Tortoisegit</a>
            </th>
            <td>장점</td>
            <td>
                1. 익숙한 TortoiseSVN 의 소스를 기반으로 개발되어 기존 Tortoise 사용자라면 UI 가 친숙함<br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>            
            <td>
                1. 기능 및 안정성이 부족함<br>
                2. Mac 용 없음<br>
            </td>
        </tr>
        <!-- //Tortoisegit -->
        <!-- Github Desktop -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193792-cf3bc000-bb87-11ea-9615-886d7e765fce.png" width="70px"><br><br>
                <a href="https://desktop.github.com/">Github Desktop</a>
            </th>
            <td>장점</td>
            <td>장점은....</td>
        </tr>
        <tr>
            <td>단점</td>
            <td>단점은....</td>
        </tr>
        <!-- //Github Desktop -->
        <!-- GitKraken -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193781-cb0fa280-bb87-11ea-8adb-a3e064a229fd.png" width="70px"><br><br>
                <a href="https://www.gitkraken.com/">GitKraken</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //GitKraken -->
        <!-- SmartGit -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193784-ccd96600-bb87-11ea-8923-f5439d8297e0.png" width="70px"><br><br>
                <a href="https://www.syntevo.com/smartgit/">SmartGit</a>
            </th>
            <td>장점</td>
            <td>
                1. Windows와 Mac, Linux를 지원한다.
                1. 비상업적 용도로는 무료로 사용할 수 있다.<br>
                2. 비용을 지불했을 경우, 향후 모든 버전에 대한 업데이트를 받는다.<br>
                3. 처음 사용할 때 디스크의 repo를 자동으로 감지한다.<br>
                4. 많이 사용되는 도구와 정보가 항상 표시되기 때문에 몇 번의 클릭만으로 사용이 가능하다.<br>
                &nbsp;&nbsp;&nbsp;ex) pull, push, sync, commit, merge와 같이 사용이 잦은 Git 명령어가 항상 상단에 표시되어 있다.<br>
                5. 표시되어 있는 도구 중 원하지 않는 것은 숨기거나 위치를 변경하는 등 패널을 재정렬 할 수 있다.(2 가지 레이아웃 사용 가능)
                5. 거의 모든 git 명령을 GUI를 통해 사용할 수 있다.<br>
                6. 모든 repository(이하 repo)가 사이드 바에 표시된다.<br>
                7. 특정 기준(e.g. files/branches/branch graph 등)에 대한 필터링이 가능하다.<br>
                8. log viewer에서 전체 commit 기록을 쉽게 알아볼 수 있다. 
                9. 제거/추가 된 문자를 강조해주어 쉽게 알아볼 수 있습니다.<br>                
                10. 위와 같은 이유로, Git에 대한 경험이 많이 없는 사람들도 쉽게 사용할 수 있다.<br>
                11. 여러 repo를 포함하는 repo 그룹을 만들 수 있다.(meta repository 역할)
                12. 한 번의 commit으로 여러 repo에서 선택한 파일들을 repo 그룹에 push할 수 있다.(모두 동일한 commit message를 사용)
                13. Git flow 기능을 지원한다.<br>
                14. 외부 도구로 확장할 수 있다.(command line 지원)
                &nbsp;&nbsp;&nbsp;ex) 메모장 또는 코드 편집기를 사용하여 이미지를 비교할 수 있다.
                15. OAuth를 사용한다면 Github, GitLab, Bitbucket 및 Atlassian Stash까지 연결하여 원격 repo에 액세스 및 관리 할 수 있다.
                16. git bridge를 통해 Mercurial과 SVN 을 모두 지원한다.
                17. GPG(보안 강화) 지원한다.
            </td>
        </tr>
        <tr>
            <td>단점</td>
           <td>
               1. 오픈소스가 아니다.<br>
               2. 상업적 이용시 비용이 발생한다.<br>
               2. 유료 버전에서만 사용할 수 있는 기능들이 있다.(e.g. Gitlab Community Edition)<br>
               3. 파일을 쉽게 탐색 할 수 없다.(설치할 때 자신에게 맞는 레이아웃으로 패널을 변경해야 한다.)<br>
               4. 업데이트에 따라 기능의 이름이 변경될 수 있다.<br>
               5. 글꼴의 크기를 변경할 수 없다.<br>
               6. 기본적으로 변경되지 않은 파일은 목록에 보이지 않는다.
            </td>
        </tr>
        <!-- //SmartGit -->
        <!-- Git Cola -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193788-ce0a9300-bb87-11ea-8beb-182d9ad68531.png" width="70px"><br><br>
                <a href="https://git-cola.github.io/index.html/">Git Cola</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //Git Cola -->
        <!-- GitForce -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193789-ce0a9300-bb87-11ea-8334-d78923f02339.gif" width="70px"><br><br>
                <a href="https://git-scm.com/download">GitForce</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //GitForce -->
        <!-- Giggle -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193786-cd71fc80-bb87-11ea-9702-0b8ffcb60d06.png" width="70px"><br><br>
                <a href="https://wiki.gnome.org/action/show/Apps/giggle?action=show&redirect=giggle">Giggle</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>            
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //Giggle -->
        <!-- Magit -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193783-cc40cf80-bb87-11ea-8b56-36e9f29d9c1a.png" width="70px"><br><br>
                <a href="https://magit.vc/">Magit</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //Magit -->
        <!-- Egit -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193785-ccd96600-bb87-11ea-96e8-1909314c2120.png" width="300px"><br><br>
                <a href="https://www.eclipse.org/egit/">Egit</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //Egit -->
        <!-- Gitg -->
        <tr>
            <th rowspan="2">
                <img src="https://user-images.githubusercontent.com/67620791/86193790-cea32980-bb87-11ea-9efd-f4cb082e7b20.png" width="70px"><br><br>
                <a href="https://wiki.gnome.org/Apps/Gitg">Gitg</a>
            </th>
            <td>장점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <tr>
            <td>단점</td>
            <td>
                1. <br>
                2. <br>
            </td>
        </tr>
        <!-- //Gitg -->
    </tbody>
<table>
    
    
### Reference
+ 도리가이드 [https://dora-guide.com/git-gui-client/]
+ 지옥에서 온 Git(생활코딩) [https://opentutorials.org/module/3746]
+ slant [https://www.slant.co/topics/2089/versus/~smartgit_vs_fork_vs_visual-studio-code]

### Images Origin
+ 각 홈페이지(CC BY )

