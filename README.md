# EEGOps EDF-Analysis

EEGOps EDF-Analysis is a browser-based EEG review and analysis workflow. It is delivered as a service
via https://eegops.com and is designed for fast, practical use in research and lab settings.

Help: https://github.com/MikeOh-SQ/eegops_help  
Contact: mikeoh@kakao.com  
Author: Kyungmin Oh, Graduate School of Psychology Innovation, Yonsei University

## What You Can Do

- Upload EDF files and review signals in a guided, step-by-step flow.
- Detect potential quality issues quickly using QC overlays.
- Apply filters and references for consistent analysis.
- Create markers and segments for experimental conditions.
- Run PSD and bandpower analysis with basic statistics.
- Export results for paper-ready reporting (tables and plots).

## Services on EEGOPS.com

- EEGOps Hub: entry point to all services.
- EEGOps EDF-Analysis: main EDF workflow.
- EEG-EDF Converter: BrainVision (.eeg/.vhdr/.vmrk) to EDF conversion.

## Data Retention Policy

- Uploaded files and results are automatically deleted after 4 hours.
- This includes EDF files, session data, previews, and conversion outputs.

## User Guide (Step by Step)

1) Import
   - Upload an EDF file.
   - Review the auto-detected channel mapping.
   - Correct mapping if needed and proceed.

2) Data-Check
   - Inspect the waveform and QC overlays.
   - Review markers (vertical lines).
   - Move forward when data looks good.

3) Filter
   - Configure HPF/LPF and notch filters.
   - Select reference channels if required.
   - Apply and preview the filtered signal.

4) Markers/Segments
   - Click the waveform to set cursor time.
   - Create markers and segment ranges.
   - Optionally restrict segments to chosen channels.

5) Analysis
   - Assign segments to Group A/B/C/D.
   - Run PSD/bandpower analysis and review statistics.
   - Use Research Summary for a one-line interpretation.
   - Export tables and plots for reporting.

## Export for Paper

- CSV: segment x band power
- CSV: summary (mean +/- sd)
- PNG: PSD plot (white background)
- PNG: bandpower plot (white background)
- JSON: full session export

---

# EEGOps EDF-Analysis (Korean)

EEGOps EDF-Analysis는 브라우저에서 EEG 데이터를 빠르게 검토하고 분석할 수 있도록 구성된
워크플로우입니다. 이 서비스는 https://eegops.com 에서 제공됩니다.

도움말: https://github.com/MikeOh-SQ/eegops_help  
문의: mikeoh@kakao.com  
제작: 연세대학교 심리과학이노베이션 대학원 오경민 (Kyungmin Oh)

## 가능한 작업

- EDF 파일 업로드 및 단계별 검토.
- QC 오버레이로 품질 이슈 빠르게 확인.
- 필터/레퍼런스 적용으로 분석 일관성 확보.
- 마커 및 세그먼트 생성으로 조건 구간 정의.
- PSD/밴드파워 분석과 기본 통계 확인.
- 논문용 테이블/그래프 내보내기.

## EEGOPS.com 서비스 구성

- EEGOps Hub: 서비스 선택 허브.
- EEGOps EDF-Analysis: EDF 분석 워크플로우.
- EEG-EDF Converter: BrainVision(.eeg/.vhdr/.vmrk) -> EDF 변환.

## 데이터 보관 정책

- 업로드 파일 및 결과는 4시간 후 자동 삭제됩니다.
- EDF, 세션 데이터, 프리뷰, 변환 결과가 모두 포함됩니다.

## 사용 방법 (요약)

1) Import
   - EDF 파일 업로드.
   - 채널 매핑 확인/수정 후 다음 단계로 이동.

2) Data-Check
   - 파형과 QC 오버레이 확인.
   - 마커(수직선) 확인.
   - 문제 없으면 다음 단계 진행.

3) Filter
   - HPF/LPF/Notch 및 레퍼런스 설정.
   - 적용 후 미리보기 확인.

4) Markers/Segments
   - 파형 클릭으로 시간 지정.
   - 마커/세그먼트 생성.
   - 필요 시 채널 제한.

5) Analysis
   - 세그먼트를 Group A/B/C/D로 분류.
   - PSD/밴드파워 및 통계 확인.
   - Research Summary로 한 줄 요약 확인.
   - 내보내기로 보고서 준비.

## 논문용 내보내기

- CSV: 세그먼트 x 밴드파워
- CSV: 요약(평균 +/- 표준편차)
- PNG: PSD 그래프(흰 배경)
- PNG: 밴드파워 그래프(흰 배경)
- JSON: 전체 세션 내보내기
