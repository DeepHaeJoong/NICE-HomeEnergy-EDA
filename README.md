# NICE-HomeEnergy-EDA
3차년도 과제 프로젝트

## 구현 LIST

        1. Real Time 재실센서에 대한 5분단위 후처리
                a) 만약 1분 단위 USM 데이터로 aggregation한다?
                        - 1분 단위 데이터를 통한 5분 단위 데이터 생성
                b) 

        2. 제어를 위한 구체적인 방식
                - 5분 단위로 On/Off
                - Scenario 1 - TV on 가정
                        - 12:00 ~ 12:05 | presence: TRUE
                        - 12:05 ~ 12:10 | presence: FALSE
                        - 12:10 ~ 12:15 | presence: FALSE
                        - TV OFF
                        
                - Scenario 2 - TV on 가정
                        - 12:00 ~ 12:05 | presence: TRUE
                        - 12:05 ~ 12:10 | presence: FALSE
                        - 12:10 ~ 12:15 | presence: TRUE
                        - TV ON
<!--                 - Scenario 3 - TV on 가정
                
                        - 12:00 ~ 12:05 | presence: TRUE
                        - 12:05 ~ 12:10 | presence: FALSE
                        - 12:10 ~ 12:15 | presence: FALSE
                        - TV OFF -->
