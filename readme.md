KakaoTalk Epic Games Notifier
Repository Description:

이 프로젝트는 에픽게임즈 스토어에서 매주 제공되는 무료 게임 이벤트에 대한 정보를 자동으로 수집하고, 해당 정보를 카카오톡을 통해 사용자에게 알려주는 애플리케이션입니다. 에픽게임즈 스토어의 데이터 수집 정책을 준수하기 위해, 이 앱은 RAPID API를 통해 무료 게임 데이터를 수집합니다. 수집된 데이터는 카카오톡 메시지 형태로 가공되어 전송됩니다.

Main Function:

RAPID API를 통한 자동 데이터 수집: 에픽게임즈 스토어의 데이터 수집 정책에 따라, RAPID API를 사용하여 매주 업데이트되는 무료 게임 목록을 안전하고 신뢰성 있게 수집합니다.
메시지 전송 자동화: 수집된 게임 정보를 카카오톡 메시지로 가공하여 사용자에게 자동으로 전송합니다.
사용자 편의성: 사용자는 매주 새로운 게임 정보를 놓치지 않고 편리하게 카카오톡으로 받아볼 수 있습니다.

모듈 설명
kakao.py: 카카오 API를 통한 메시지 전송을 위한 토큰 발급 및 갱신하는 기능을 담당합니다.
info.py: RAPID API를 통해 에픽게임즈의 무료 게임 이벤트 정보를 수집합니다.
template.py: 수집된 게임 정보를 카카오톡 피드 형태의 메시지 템플릿으로 생성합니다.
send.py: 생성된 메시지 템플릿을 카카오톡으로 사용자에게 전송하는 기능을 수행합니다.
app.py: 위 모든 모듈을 사용하여 매주 업데이트되는 무료 게임 정보를 사용자에게 자동으로 보내는 실행 파일입니다.


이 앱은 NAVER CLOUD PLATFORM을 통해 자동화되어 배포되었습니다. 이 프로젝트와 관련된 더 자세한 정보와 사용 방법은 제 블로그에서 확인할 수 있습니다.