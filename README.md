# SmartFactory2_TadGAN-USAD

Final Project for Smart Factory Capstone Design2

업로드 날짜: 2022-12-06


실행순서
1. Transformation 폴더안의 dwt파일: IoT센서 상에서 수행되는 과정으로 이산 웨이블릿 변환을 하여 수집된 신호 데이터에서 이상치와 정상치가 잘 구분되도록 신호를 변환함.

2. Communication 폴더안의 파일들: IoT센서에서 Edge Device로 데이터를 전송하는 과정으로 서버와 클라이언트 파일를 주석처리된 번호 순서되로 순차적으로 실행함.

3. Anomaly Detection 폴더안의 파일들: 앞서 생성된 dwt결과 파일을 바탕으로, GAN과 Auto Encoder를 이용하여 이상감지를 한다.

*모든 파일의 디렉토리는 제 로컬PC를 기반으로 설정되어 있으므로 실행하시는 환경에 맞춰 변경이 반드시 필요합니다.
