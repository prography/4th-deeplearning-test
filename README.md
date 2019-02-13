
# Prography 4th Deep Learning Test
Image Classification with own dataset


## How to do ?
주어진 데이터셋으로  Classification 모델을 구축하는 것이 목적이에요 !!  
아래의 가이드를 만족하는 train.py , test.py, models.py 를 작성해주세요.  

**제출물 : train.py , test.py, models.py, mymodel.pth(or .ph)**

제출물의 이름은 위와 동일하게 제출해주세요.  
위의 4가지 항목을 압축하여 '지원자이름.zip' 형태로 압축하여 제출해주세요.  
(압축 포맷은 .zip, .tar, .tar.gz 의 3가지로 사용)  


## Guide
**Pytorch 사용을 권장합니다**


### train.py
([ ] 안의 사항은 arguments를 의미)
<pre><code> train.py [trainingset_folder] </code></pre>  
(ex)  
<pre><code> train.py datasets/train </code></pre>
위와 같은 커맨드를 입력하였을 때, 모델 트레이닝이 진행될 수 있도록 작성해주세요.


### test.py
([ ] 안의 사항은 arguments를 의미)
<pre><code> test.py [testset_folder] [model_name] </code></pre>
(ex)  
<pre><code> test.py datasets/test mymodel.pth </code></pre>
위와 같은 커맨드를 입력하였을 때, 학습된 모델의 테스트 결과가 나올 수 있도록 작성해주세요.  
테스트 결과를 표출하는 형태에 대한 별도의 양식 및 규정은 존재하지 않습니다  


### models.py
models.py 에는 train.py에서 사용할 모델이 포함되어 있도록 작성해주세요. (train.py 에서 import해서 사용)  
프레임워크(tensorflow, pytorch, keras 등)에서 기본적으로 구현되어 있는 모델은 사용 불가합니다  
오픈소스를 사용하는 것은 가능합니다  


### model.pth (or model.ph)
학습이 완료된 모델파일입니다.


## Datasets
하단 구글 드라이브 링크를 통해 데이터셋을 다운로드 받아주세요 !  
<pre><code> https://drive.google.com/open?id=1gMRZ4nhxuIo2Ub0lPzBDu1OMXQPZTfQp </code></pre>


## Rules.
**지원자가 많아지게 되면, 정확도를 기준으로 오름차순으로 선발이 될 수 있습니다**   
**정확도는 보내주신 코드를 그대로 실행하여 산출할 예정입니다.**
