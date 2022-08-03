## 유튜브 댓글 전처리와 LDA 토픽모델링을 사용한, 삼성전자 폴더블폰에 대한 대중의 반응 분석

Graduation_Thesis repository에 수록된 코드들은 *한국외국어대학교 언어인지과학과 2022년 1학기 졸업논문 주제* 인 
'유튜브 댓글 전처리와 LDA 토픽모델링을 사용한, 삼성전자 폴더블폰에 대한 대중의 반응 분석'에 활용되었습니다.

* 유튜브 댓글을 크롤링하여 대량의 텍스트 데이터 속에서 삼성전자 폴더블폰 제품인 **'갤럭시 Z flip'** 과 **'갤럭시 Z fold'** 에 대한 대중의 반응을 분석했습니다.
* 텍스트 정제 및 정규화로 텍스트 전처리 과정을 수행하였습니다.
* 전처리를 거친 텍스트를 활용하여 **'빈도분석'** 과 **'LDA 토픽모델링 분석'** 을 수행하여 토큰들의 관계를 분석하고 대중의 반응을 분석했습니다.

***

## 유튜브에서 댓글 수집(크롤링)하기
* flip,fold_Youtube_comments_crawling.ipynb 파일을 이용했습니다.
* url에 Z flip 또는 Z fold 제품후기 유튜브 영상 url을 입력하면 댓글이 자동으로 추출됩니다.

