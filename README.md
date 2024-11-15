# 2024 COMPASS Hackathon 출품작
2024년 11월 9일(토)에 진행된, [COMPASS Hackathon](https://www.lecturernews.com/news/articleView.html?idxno=166069)에 참여하여, [우수상(3등)](https://cloud.gwlrs.ac.kr/ko/exo/all/view/131/notice/view/858)으로 입상했습니다! (Team: Data Doctors)  
![KakaoTalk_20241115_220703965](https://github.com/user-attachments/assets/98cd4942-c667-44c6-8013-1459f63e87ce)

COMPASS 플랫폼을 활용하여 OMOP-CDM 기반 정밀의료·헬스케어 등 의생명데이터를 분석하는 경진대회에서,  
**Alzheimer's disease**, **estrogen**, **cardiovascular disease** 간의 관계에 대한 탐구를 주제로 하여 분석을 진행했습니다.  

## Poster
탐구의 개요와 분석 절차를 개략적으로 담은 포스터입니다.  

![KNU Hackathon poster submission - Data Doctors_1](https://github.com/user-attachments/assets/d9df87f3-e4bb-4e00-99b1-40f3f63191e7)

## Presentation slides
Poster session에서 통과한 이후,  
본격적인 분석 절차와 결과를 담은 PPT slides를 토대로 발표를 진행했습니다.  

![COMPASS_Hackathon_presentation_Data_Doctors_1](https://github.com/user-attachments/assets/03ca1205-1b2b-4af1-8d93-f9e59fa46dad)
![COMPASS_Hackathon_presentation_Data_Doctors_2](https://github.com/user-attachments/assets/cc8d42b9-5452-48a9-801d-c4a158b5f8f5)
![COMPASS_Hackathon_presentation_Data_Doctors_3](https://github.com/user-attachments/assets/86a3ff7c-41bf-4c9b-9678-537f0a5da34b)
![COMPASS_Hackathon_presentation_Data_Doctors_4](https://github.com/user-attachments/assets/1cdbb4ea-21aa-4609-8e85-71bedcfe405b)
![COMPASS_Hackathon_presentation_Data_Doctors_5](https://github.com/user-attachments/assets/938ea4a5-0b27-45f9-96c3-fb31e12b35a1)
![COMPASS_Hackathon_presentation_Data_Doctors_6](https://github.com/user-attachments/assets/04b52a18-8b4f-41df-8b6f-85f588510140)
![COMPASS_Hackathon_presentation_Data_Doctors_7](https://github.com/user-attachments/assets/54928457-05ec-49f3-8103-01a09117cc2f)
![COMPASS_Hackathon_presentation_Data_Doctors_8](https://github.com/user-attachments/assets/8b070b9c-6f46-4513-89b1-682f82416d09)
![COMPASS_Hackathon_presentation_Data_Doctors_9](https://github.com/user-attachments/assets/795e8c94-5687-44e9-98c4-a9bdb2748c52)
![COMPASS_Hackathon_presentation_Data_Doctors_10](https://github.com/user-attachments/assets/349ac847-1b28-447e-835d-ea23730d3915)
![COMPASS_Hackathon_presentation_Data_Doctors_11](https://github.com/user-attachments/assets/3d4c0ced-9a47-4a66-a583-bb7864c318d7)
![COMPASS_Hackathon_presentation_Data_Doctors_12](https://github.com/user-attachments/assets/28574dec-fb07-4a79-b5ef-c71bd583c4fe)
![COMPASS_Hackathon_presentation_Data_Doctors_13](https://github.com/user-attachments/assets/2194c270-039e-4adc-a0c6-340a094a2ea9)
![COMPASS_Hackathon_presentation_Data_Doctors_14](https://github.com/user-attachments/assets/d67b763a-6bc6-4d32-a21b-b4e8b2a414bb)
![COMPASS_Hackathon_presentation_Data_Doctors_15](https://github.com/user-attachments/assets/0ac60090-69e3-4d8a-bd83-0b0eaff2327d)
![COMPASS_Hackathon_presentation_Data_Doctors_16](https://github.com/user-attachments/assets/6bb00076-2ab4-490d-b3ac-b61f69bf96f6)
![COMPASS_Hackathon_presentation_Data_Doctors_17](https://github.com/user-attachments/assets/fe2c5a24-a040-4262-bfae-af157595449f)
![COMPASS_Hackathon_presentation_Data_Doctors_18](https://github.com/user-attachments/assets/403a2460-1051-4249-b2c0-7cdcf180d4e1)
![COMPASS_Hackathon_presentation_Data_Doctors_19](https://github.com/user-attachments/assets/521b9a90-b0ce-4f3e-9b8b-7c41d95fd0bd)
![COMPASS_Hackathon_presentation_Data_Doctors_20](https://github.com/user-attachments/assets/5d05540f-ab12-4e20-9b9f-602258f7f22f)
![COMPASS_Hackathon_presentation_Data_Doctors_21](https://github.com/user-attachments/assets/20b47d94-aef9-40fc-8e4e-be4be40d49b7)
![COMPASS_Hackathon_presentation_Data_Doctors_22](https://github.com/user-attachments/assets/14bf6a91-7a31-455e-b4fa-b12006abb882)
![COMPASS_Hackathon_presentation_Data_Doctors_23](https://github.com/user-attachments/assets/f0ce6ebf-d11d-4e6c-b17c-5817095d5cc7)

## For improvement...
Majority class와 Minority class 간의 **imbalance**가 굉장히 심하기 때문에, **model의 성능이 매우 아쉬웠습니다.**   
분석에서 적용한 *weight balancing* 기법 외에,
- Oversampling: SMOTE, SMOTEENN, SMOTE-Tomek, etc.
- Undersampling: Random undersampling, Tomek links, ENN, etc.  
위 기법들을 활용하여 model의 성능을 높여보고자 합니다.

이를 위해, notebook을 직접 작성하여 업로드할 예정입니다.
