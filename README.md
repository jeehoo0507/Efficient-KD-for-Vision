# Efficient Knowledge Distillation for Vision

## 랩미팅 발표 자료

작은 학생 모델을 만드는 데 드는 학습 비용에서 출발했다. 교사를 덜 실행하면 그만큼 시간이 줄어들까? 비용 일부가 선택·사전 계산·저장으로 옮겨가거나, 평균 정확도에 가려진 그룹에서 손실이 생길 수도 있다. 이 두 가능성을 세 질문으로 나누어 조사했다.

[본 발표 16장 + 질의응답 3장 PPTX](presentations/vision-kd-seminar/EKD-seminar.pptx) · [페이지별 샘플과 설명](presentations/vision-kd-seminar/README.md) · [실험 색인과 조건별 집계](presentations/vision-kd-seminar/experiment-index.md) · [원고 그림 1–4와 표 1–6](presentations/vision-kd-seminar/originals/README.md)

- [Ⅰ. 논문 구상과 문헌 근거](presentations/vision-kd-seminar/README.md#paper)　한 스텝의 연산을 분해한 뒤, 같은 교사 호출을 줄여도 학생이 받는 신호가 어떻게 다른지 살펴본다. 이 틀을 문헌 40편에 적용해 직접 비교가 필요한 지점을 찾는다.
- [Ⅱ. 실험 설계와 결과](presentations/vision-kd-seminar/README.md#tests)　세 데이터셋에서 네 축을 비교하고 CelebA에서 두 축을 추가 점검했다. 100에폭 Full KD로 비용 절감률을 구하고, 60·70에폭 Full KD로 비슷한 시간에서 얻는 정확도를 비교한다.
- [Ⅲ. 세 질문의 답과 논의](presentations/vision-kd-seminar/README.md#decisions)　관찰한 비용 이동과 성능 차이를 근거로 각 기법에 필요한 보고 항목을 제안한다. 문헌 40편과 직접 시험한 모델·데이터가 결론의 적용 범위다.
- [질의응답용 보조 실험](presentations/vision-kd-seminar/README.md#questions)　CNN 검증, Waterbirds 세 시드와 검증·테스트 차이, Aircraft 보조 지표를 필요할 때 연다.
