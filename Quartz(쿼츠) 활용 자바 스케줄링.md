# Quartz(쿼츠) 활용 자바 스케줄링



Quartz(쿼츠)는 Java 언어를 통해 구축된 프로그램 작업을 스케줄링하기위해 사용하는 java Scheduling 라이브러리입니다. Java 소스코드 단계에서 작업 스케줄링이 가능하며, 다중 Thread Architecture 기반으로 동작합니다.



* 주요 Interface

  `Scheduler` - 스케줄링을 위한 기본 API

  `Job` - 실질적인 작업 수행 개체

​		`JobDetail` - Job 인스턴스 정의를 위해 사용

​		`Trigger` - Job(작업) 수행 일정을 위해 사용(시간, 횟수, 주기 등)

​		`JobBuilder` - JobDetail 생성을 위해 사용

​		`TriggerBuilder` - Trigger 생성을 위해 사용









크론탭을 이용해 리눅스 OS 단계에서 스케줄링이 가능하지만,

자바 소스 단게에서도 스케줄링이 가능합니다.



Quartz(쿼츠)를 활용해 자바 소스 단계에서 앱을 스케줄링하는 방법을 살펴보겠습니다.























































