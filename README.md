저는 이 연구에서 데이터의 출처를 밝힙니다. ReLU나 다른 Activation function보다 ELU, CELU가 정확도가 95.2까지 보이며 높았고, VGG19가 RESNET151보다 높은 정확도를 가져왔습니다. 데이터 augmentation기법을 이용했을 경우, 정확도가 더 떨어진 것을 포착했습니다.
Activation function은 Accuracy에 2%까지 영향을 미치기 때문에, 더욱더 중요해짐을 강조합니다.
데이터는 kaggle에서 covid lung, normal lung 이미지들을 여러곳에서 모아, 불필요 해보이는 사진들, covid가 아닌 폐렴사진들, 의료기계들이 많이 부착된 사진들, 옆면사진들, ct사진들, 흐릿한 사진들, 다른 물체가 포착된 사진들을 모두 삭제하였습니다.


1. Chest X-Ray Images (Pneumonia)
Paul Mooney · Updated 5 years ago
Usability 7.5 · 2 GB
5856 Files (other)
chest x-ray woth poor inspiration (A) ches PA bilateral increased density, both middle, loswer lung fields, suspicious of pneuminia(aprrow tips). poor inspiration(7 posterior costal arches are identified) and voluminous breast. (B) same patient. Repaeat chest PA few minutes agter forced inspiration, all above-metntioned findings are no longer seen(note the change in the morphology of the cardiac silhouette). (c) artefact dye to high breast density, Bilateral symmetrical opacities in lower fields due to highly dense breaest tissue
https://www.kaggle.com/search?q=covid-19+xray+datasetFileTypes%3Apng+datasetFileTypes%3Ajpg

2.(253MB), COVID-19 chest xray 
https://www.kaggle.com/datasets/bachrr/covid-chest-xray

3.(184MB),Chest Xray for covid-19 detection 
https://www.kaggle.com/datasets/fusicfenta/chest-xray-for-covid19-detection

4.(43MB), COVID-19 Chest X-ray Image Dataset 
https://www.kaggle.com/datasets/alifrahman/covid19-chest-xray-image-dataset

5. COVIDx CXR-3 / (CXR = Chest X-Ray) 
코로나넷팀
https://www.kaggle.com/datasets/andyczhao/covidx-cxr2
데이터의 출처는 코로나 양성 데이터는 RICORD, cohen, sirm,. Actmed, stonybrook, bimcv였다 여기서, 난잡해 보이는 이미지를 모두 제거했다.
코로나 음성 데이터는 주로 RSNA
Test dataset
음성 rsna
양성 ricord
Trian data set
MIDRC-RICORD-1C-SITE2 / ricord 데이터 모두 양성 -> 부분적으로 사용
Na-chest / Stonybrook 데이터 모두 양성 -> 부분적으로 사용 - 했음
sub-s  / Bimcv 데이터 모두 양성 -> 의료부착기기 이미지만 고르기
Rsna 모두 음성

6. COVID19_Pneumonia_Normal_Chest_Xray_PA_Datasetd 
https://www.kaggle.com/datasets/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset?select=pneumonia

7. COVID 19 Xray Image Dataset with Huge Samples /(no reference)
https://www.kaggle.com/datasets/mr3suvhro/covid-19-xray-image-dataset-with-huge-samples

8. covid19
https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset
