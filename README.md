Useage
===========

requirements
환경 구축
Link: https://github.com/tensorflow/magenta/blob/master/README.md

training, evaluation, datasets 들은 포함하지 않음. 용량 너무 커~
generation에 필요한 run 파일과 소스코드만 포함시킴.

필요한 실행 파일
polyphony_rnn 폴더에 있음.
생성은 polyphony_rnn_generate.py 만 있으면 됩니다.

실행 방법
python polyphony_rnn_generate.py \
 --run_dir=category/[원하는카테고리]/run
 --output_dir=원하시는_아웃풋_경로
 --num_outputs=아웃풋_개수
 --num_steps=음악_길이(128이 제일 적당함.)

Happy 말고는 학습시켜둔 파일들이 다 날라가서 ^^;;;
Happy만 정상적으로 나오실 겁니다.
