# AI
먼저 git clone 받은 뒤 터미널에서 pip install -r requirments 합니다.
터미널에서 python detect.py --weights runs/train/plant_yolov5_result3/weights/best.pt --img 416 --conf 0.5 --source 0 코드를 입력해 줍니다.
위 코드에서 img는 img 사이즈이고 source는 몇번 째 캠을 쓸거냐 입니다 노트북을 사용하실 때 노트북에 내장되어있는 캠 말고 다른 캠을 연결 하고 쓰실거라면 0 대신 1로 바꿔주세요
