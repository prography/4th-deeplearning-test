# Prography 4th Deep Learning Test
Image Classification with own dataset


## How to do ?
주어진 데이터셋으로  Classification 모델을 구축하는 것이 목적이에요 !!  
아래의 가이드를 만족하는 train.py , test.py, models.py 를 작성해주세요.  

**결과물 : train.py , test.py, models.py, mymodel.pth(or .ph)**

결과물의 이름은 위와 동일하게 해주세요.  

결과물은 지원서에 제출한 Github 주소에 올려주시면 됩니다.
모델파일은 README를 통하여 구글드라이브나 드랍박스 다운받을 수 있는 링크를 표기해주세요.  

**목요일 자정 이전의 커밋까지만 결과물이 인정됩니다.**  
**Repository 이름은 -(하이픈) 으로 연결해주세요**  
**형식을 지켜주시지 않는 경우에 불이익이 발생할 수 있습니다.**  


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
프레임워크(tensorflow, pytorch, keras 등)에서 기본적으로 구현되어 있는 모델은 사용 불가합니다 (ex: torchvision.models.VGG)  
오픈소스를 사용하는 것은 가능합니다.  


### model.pth (or model.ph)
학습이 완료된 모델파일입니다.


## Datasets
하단 구글 드라이브 링크를 통해 데이터셋을 다운로드 받아주세요 !  
<pre><code> https://drive.google.com/open?id=1gMRZ4nhxuIo2Ub0lPzBDu1OMXQPZTfQp </code></pre>


## Help
**위의 사전 과제는 지원자분들의 실력파악을 위함입니다. 사전 과제로 합격/불합격이 결정되지는 않습니다.**
궁금하신 사항은 아래 연락처로 편하게 문의주세요 :)
사전과제에 관한 직접적인 질문은 받지 않습니다.

조성만 : 010-3101-0814
장원범 : 010-3793-7352
