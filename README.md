# Pythonmachine-Project
파이썬머신러닝 코드 및 데이터 저장
hatra3 는
trainer.save_model("/content/drive/MyDrive/hatra3")
tokenizer.save_pretrained("/content/drive/MyDrive/hatra3")
로 저장된 학습이 완료된 파일들,

thelast2_utf 는 전처리까지 완료된 파일
fine_ha_utf는 전처리 완료한 파일을 학습시키기 위해 QA형태로 변환한 파일
입니다.

모델 학습시에는 
버전들은 각각 accelerate==0.29.3 peft==0.10.0 bitsandbytes==0.43.1 transformers==4.40.1 trl==0.8.6 datasets==2.19.0
로 진행하였습니다.
