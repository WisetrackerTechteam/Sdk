### WiseTracker SDK 의 업데이트 정보. 
###### WiseTracker에서 제공하는 SDK와 관련된 업데이트 내역은 아래에서 제공합니다. 
###### 업데이트 내용에 대해서 기술적 질문 사항은 tech@wisetracker.co.kr로 문의해주시기 바랍니다. 

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
