
git download path
git\webProject001\eGovFrame_jqwidget001 -> right click then "import project"




----------------------------------------------------------------------------------------------------------------------------------


MAIN SPEC
-개발자용 개발환경 32&64bit(Implementation Tool) Full Version 3.7.0
 ( http://www.egovframe.go.kr/cop/bbs/selectBoardArticle.do?bbsId=BBSMSTR_000000000002&nttId=1408&menu=3&submenu=2&leftsub=2 )

SUB SPEC
-Eclipse Neon.3 Release (4.6.3) 적용
-JAVA 8 적용 (이클립스 구동 시 JDK 1.8 필수)
-Maven 3.3.9 적용
-Spring Core 3.8.4
-IBATIS

middle ware
-jquery 3.3.1
-jqueryUi 1.12.1


server
-tomcat 9
 ( https://tomcat.apache.org/download-90.cgi  ////  http://mirror.apache-kr.org/tomcat/tomcat-9/v9.0.10/bin/apache-tomcat-9.0.10-windows-x64.zip )
 
 
 start page
 -http://localhost:8080/sht_webapp/
 
 
 
 ----------------------------------------------------------------------------------------------------------------------------------------
 
 -maven 오류 문제
 http://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev3.7:gettingstarted
 
 --> 
Maven 설정파일 및 종속라이브러리를 포함한 maven repostiory 3.7 를 다운로드 한다.
다운로드 받은 파일은 임의의 디렉토리에서 압축해제한다.(압축해제한 디렉토리는 [MavenRepository 설치디렉토리] 로 명명한다.)
텍스트 에디터를 이용하여 [MavenRepository 설치디렉토리]/settings.xml 파일의 localRepository 항목의 값을 다음과 같이 수정한다.

<settings>
        ...
    <localRepository> [MavenRepository 설치디렉토리]/repository </localRepository>
        ...
</settings>
1)아래 파일 다운로드 한후 내용을 위와 같이 경로 바꾸고 C:\Users\[사용자]\.m2 에 복사
http://www.egovframe.go.kr/wiki/lib/exe/fetch.php?media=egovframework:dev3.7:settings_3_7.zip

2)아래 파일 다운로드 한후 C:\Users\[사용자]\.m2\repository 안에 기존내용 삭제 후 압축히제
http://maven.egovframe.kr/publist/HDD1/public/egovframework_v3.7/2_DevelopmentEnvironment/maven_repository_3_7.zip








