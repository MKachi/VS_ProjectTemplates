# Visual Studio Project Templates
Visual Studio의 C++ project template 입니다.  
  
#### 설정 정보
* **출력 디렉터리**
    `$(SolutionDir)\Build\Products\$(PlatformTarget)_$(Configuration)\`
* **중간 디렉터리**
    `$(SolutionDir)\Build\Intermediates\$(PlatformTarget)_$(Configuration)\`
* **추가 포함 디렉터리**
    `$(ProjectDir)include`
* **전처리기 정의**
    * Console : `[ _WINDOWS ]`
    * Dynamic : `[ _WINDOWS, DLL_EXPORTS ]`
    * Static : `[ _WINDOWS ]`
  
#### 설치 방법
`C:\Users\{사용자 이름}\Documents\{Visual Studio 버전별 폴더}\Templates\ProjectTemplates\Visual C++ 프로젝트`  
위의 경로에 Bin폴더에 있는 `.zip` 파일 복사