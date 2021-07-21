## 나중에 사용할 수 있도록 Cloud Shell 준비 

1. 아래 자격 증명을 사용하여 Azure Portal(+++https://portal.azure.com+++)에 로그인합니다. 

 

    ||| 

    |--|--| 

    |사용자 이름|+++@lab.CloudPortalCredential(User1).Username+++| 

    |암호|+++@lab.CloudPortalCredential(User1).Password+++| 

 

1. Azure Portal 맨 위에 있는 도구 모음에서 **Cloud Shell** 아이콘을 선택합니다. 

 

1. Azure Cloud Shell 시작 대화 상자에서 **Bash**를 선택합니다. 

 

1. 탑재된 스토리지가 없음 화면에서 **고급 설정 표시**를 선택합니다. 

 

1. 고급 설정 화면에서 다음 필드를 채운 후에 **스토리지 만들기**를 클릭합니다. 

 

    ||| 

    |--|--| 

    |리소스 그룹| 기존 리소스 그룹 사용: **cloud-shell-storage-eastus**| 

    |지역| **미국 동부** | 

    |스토리지 계정(새로 만들기)|+++cloudshell@lab.LabInstance.Id+++| 

    |파일 공유(새로 만들기)|+++shellstorage+++| 

     

  >[!KNOWLEDGE] "테넌트 사용자 초과 할당량" 오류가 발생하면 **Cloud Shell 지역**을 다른 지역으로 변경합니다. 

 

1. Cloud Shell이 초기화되고 텍스트 프롬프트가 표시되면 셸을 종료합니다. 
