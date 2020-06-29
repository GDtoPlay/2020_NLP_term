# Korean

한국어 데이터 (nsmc) 작업물들 입니다.

- data :  산출물 저장 폴더
- data_and_txt_csv_conv : csv <-> txt 변환 파일 + 산출물
- HanBert-nsmc : HanBert
- KoBERT-nsmc : KoBERT
- KoELECTRA : KoELECTRA
- sub_koBERT : 기타 작업물 (KoBERT 작업 시도)

# English
영어 데이터 (Friends) 작업물 입니다.

- BERT_MAX : BERT_MAX

## 코드 실행

- HanBert-nsmc : 폴더 내 Hanbert_run_linux_command.ipynb 이용  (사전에 [HanBert-54kN-torch](https://drive.google.com/file/d/1LUyrnhuNC3e8oD2QMJv8tIDrXrxzmdu4/view)을 받고 "HanBert-nsmc/HanBert-54kN-torch"으로 이동 필요)
 

- KoBERT-nsmc : 폴더 내 KoBERT_run_linux_command.ipynb 이용

- KoELECTRA : finetune/predict.ipynb 사용하여 작업 (미완성)

- BERT_MAX : 폴더 내 en_runner.ipynb 이용, Friends 폴더에 결과 csv 저장됨


## 참고사항

- 깃에 vm에 저장했던 모델들을 올릴 수 없어 빠진 상태 

- csv 생성(txt 생성) 코드에는 이전 모델의 위치 같은 것이 하드 코딩 됨

- 따라서 csv 파일 생성 테스트를 위해서는 학습과 코드 수정이 필요 (모델 path 같은 것)

## 참고한 깃 링크들

- <https://github.com/monologg/HanBert-nsmc> (HanBert-nsmc)
- <https://github.com/monologg/KoBERT-nsmc> (KoBERT)
- <https://github.com/monologg/KoELECTRA> (KoELECTRA)

- <https://github.com/KisuYang/EmotionX-KU> (BERT_MAX)

- <https://github.com/SKTBrain/KoBERT> (KoBERT)