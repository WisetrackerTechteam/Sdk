### WiseTracker SDK 의 업데이트 정보. 
###### WiseTracker에서 제공하는 SDK와 관련된 업데이트 내역은 아래에서 제공합니다. 
###### 업데이트 내용에 대해서 기술적 질문 사항은 tech@wisetracker.co.kr로 문의해주시기 바랍니다. 

* Facebook 분석 방식 변경.
> 1. 라이브러리 (Fb/Basic) 구분 제거.
> 2. 페이스북 분석 방법, 함수 제공.

* 회원 ID 수집 항목 추가.
> 1. 업데이트 내용 : SDK에서 회원 ID항목을 수집할수 있도록 함수 추가.
> 1. iOS & Android SDK 21.2.50
> 1. 배포 일자 : 2018.11.08

* Apple SearchAd 광고 분석 지원 
> 1. 업데이트 내용 : Apple SearchAd 광고 분석이 가능하도록 iOS SDK 업데이트 반영. 
> 1. iOS SDK 21.2.48
> 1. 배포 일자 : 2018.09.20

* 단말기에서 추출한 시간정보값이 사용자에 의해서 현재 Network Time과 차이가 발생하는 경우에 대한 예외 처리. 추가. 
> 1. 업데이트 내용 : 사용자의 부주의 또는 의도한 단말기 시간 변경으로 인해서 System.currentTimeMillis()추출값이 현재 네트워크에서 사용하는 시간값과 다른 부분을 대응하기 위한 패치. 
> 1. Android SDK 21.2.48
> 1. 배포 일자 : 2018.05.18

* Android Oreo ( API 26 ) 환경에서 Background Service 제한에 따른 보완 조치 사항 적용. 
> 1. 업데이트 내용 : Android Oreo ( API 26 ) 이상에서 Background 에서의 service 생성 제한에 대응하는 패치사항 적용. 
> 1. Android SDK 21.2.47
> 1. 배포 일자 : 2018.05.03

* WebView로 로딩된 웹 페이지에 재진입 하는 경우에 대한 reInjectXXXX Crash 수정 
> 1. 업데이트 내용 : reInjectWKTracker 함수에서 NSInvalidArgumentException 오류 현상 예외 처리. 
> 1. iOS SDK 21.2.47
> 1. 배포 일자 : 2018.04.24

* WebView로 로딩된 웹 페이지에 재진입 하는 경우에 대한 reInjectXXXX 함수 추가. 
> 1. 업데이트 내용 : 웹뷰에 최초 로딩된 페이지에 다시 진입하는 경우 웹 페이지를 리로딩 하지 않고, id를 지정하여 inject할수 있는 함수 추가. ( reInjectXXXX 함수 )
> 1. Android SDK 21.2.46, iOS SDK 21.2.46
> 1. 배포 일자 : 2018.03.28

* 화면 분석 API 추가 및 클릭 이벤트 분석 전용 API 추가.
> 1. 업데이트 내용 : 화면 분석을 위한 API 추가 ( injectFinishedWithOutStartEndPage, endStartPage )
                 클릭이벤트 분석 전용 API 추가 ( sendClickData )
> 1. Android SDK 21.2.45, iOS SDK 21.2.45
> 1. 배포 일자 : 2018.03.06

* iOS에서 installTime 관련 crash 보고 현상에 대한 패치.
> 1. 업데이트 내용 : 기존 앱 설치자의 앱 업데이트시 신규 sdk적용에 의한 installTime Crash 현상에 대한 조치. 
> 1. iOS SDK 21.2.44
> 1. 배포 일자 : 2018.02.07

* Android에서 InstallReferrerClient Library 적용.  
> 1. 업데이트 내용 : Android 에서 보다 정확한 CTIT 계산을 위해서 업데이트된 Library가 추가 되었습니다. 이 버젼을 사용할 경우 build.gradle 파일에 installreferrer를 설정해줘야 합니다.  
> 1. Android SDK 21.2.44
> 1. 배포 일자 : 2018.01.08

* IOS에서 country code 추출시 발생하는 Crash 현상 개선. 
> 1. 업데이트 내용 : IOS에서 country code 추출시 발생하는 Crash 발생 가능성에 대한 예외 처리 추가. 
> 1. IOS SDK 21.2.43
> 1. 배포 일자 : 2017.12.20

* Android 앱설치시 Desktop 환경에서의 설치에 따른 광고분석 보완조치 적용. 
> 1. 업데이트 내용 : Android의 경우에 Desktop 에서 Google Account를 통해서 앱을 설치하고 광고를 통해 유입되는 케이스에 대한 보완조치 적용. 
> 1. Android SDK 21.2.43
> 1. 배포 일자 : 2017.12.15

* 안정화 및 코드 개선 적용. 
> 1. 업데이트 내용 : Android의 경우 권한 획득 관련하여 READ_PHONE_STATE 권한을 옵션사항으로 변경하였으며, ios의 경우 보고된 예외 사항에 대한 코드 보완 조치가 적용되었습니다.
> 1. Android SDK 21.2.42 ,  Ios SDK 21.2.42
> 1. 배포 일자 : 2017.11.10

* 푸시 메시지 클릭수 분석을 위한 API 추가. 
> 1. 업데이트 내용 : 푸시 메시지를 클릭한 클릭 횟수 측정을 위한 api가 추가되었습니다.
> 1. 이 버전의 sdk사용시 푸시메시지를 클릭한 횟수의 분석을 정확하게 분석 가능합니다.
> 1. Android SDK 21.2.41 ,  Ios SDK 21.2.41
> 1. 배포 일자 : 2017.10.20

* 클릭 이벤트 분석을 위한 API 추가. 
> 1. 업데이트 내용 : 기존의 클릭 이벤트를 분석하는 방법을 개선하여, 버튼의 클릭수 분석을 강화하였습니다. 
> 1. 이 버전의 sdk사용시 좀더 다양한 상황에서 정교하게 버튼 클릭수 분석이 가능합니다.
> 1. Android SDK 21.2.40 ,  Ios SDK 21.2.40
> 1. 배포 일자 : 2017.09.27

* IOS에서 보고된 Crash 현상과 관련하여 BAD_ACCESS 현상 개선. 
> 1. 업데이트 내용 : 단말기의 리소트가 부족한 경우, BAD_ACCESS 예외가 보고되어, 이 부분을 pointer를 사용하여 보완조치함. 
> 1. 이 버전의 sdk사용시 TinyDB, QueueFile과 관련된 참조오류 현상이 개선됩니다. 
> 1. IOS SDK 21.2.39
> 1. 배포 일자 : 2017.09.01

* Android에서 보고된 ANR현상과 관련하여 SharedPreferences 관련 로직 개선.
> 1. 업데이트 내용 : Android os가 제공하는 SharedPreferences를 사용함에 있어서, editor.commit() 함수 사용하는 경우에는,
                  ANR이 발생할 수 있는 기술적 내용이 리퍼런스를 통해서 확인되어, 
                  이 부분을 .apply() 함수로 ( 비동기 처리 )로 업데이트 하였습니다. 
> 1. 이 버전의 sdk사용시 위에 보고된 ANR 현상에 대해서 대응이 가능합니다. 
> 1. Android SDK 21.2.38
> 1. 배포 일자 : 2017.08.18

* 서버투서버 데이터 수집을 위한 라이브러리 추가 수정. 
> 1. 업데이트 내용 : 기존의 라이브러리 기능에서, 추가적으로 광고 분석정보도 같이 추출되어 서버투서버 통신이 가능하도록 라이브러리가 변경되었습니다. 
> 1. 이 버전의 sdk사용시 서버투서버 통신에 의한 데이터에서도 연속적인 광고 채널 정보 분석이 가능합니다. 
> 1. Android SDK 21.2.37 ,  Ios SDK 21.2.37
> 1. 배포 일자 : 2017.08.08

* 하위 미디어 분석관련 항목 추가 ( _wtbffid ) 
> 1. 업데이트 내용 : 기존의 하위미디어 분석관련 파라미터 ( _wtaffid ) 의 하위 미디어에 대한 분석을 지원하기 위해서, _wtbffid 분석 항목이 추가되었습니다.
> 1. 이 버전의 sdk사용시 기존의 광고 채널, 캠페인별 제휴사의 하위미디어까지 분석이 가능하게 됩니다.
> 1. Android SDK 21.2.36 ,  Ios SDK 21.2.36
> 1. 배포 일자 : 2017.08.03

* 주간순수방문자 측정항목 추가
> 1. 업데이트 내용 : 기존의 일요일 ~ 토요일 기준의 주간순수방문자수와 별도로 월요일 ~ 일요일기준의 주간순수방문자수 측정항목 추가되었습니다.
> 1. 이 버전의 sdk사용시 두가지 기준의 주간순수방문자수 데이터 확인이 가능합니다.
> 1. Android SDK 21.2.35 ,  Ios SDK 21.2.35
> 1. 배포 일자 : 2017.08.01
