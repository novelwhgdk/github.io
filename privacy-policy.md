---
title: "개인정보처리방침"
---

# 모두의 일정 개인정보처리방침  
**시행일:** 2025‑07‑17

> 본 방침은 「개인정보 보호법」·「정보통신망 이용촉진 및 정보보호 등에 관한 법률」 등 관련 법령에 따라, **모두의 일정**(이하 “회사”)이 제공하는 일정 관리·공유 서비스(이하 “서비스”)에서 처리되는 개인정보의 수집·이용·보관·파기 및 이용자 권리 등을 설명합니다.

---

## 1. 수집하는 개인정보 항목

| 구분 | 수집 시점 | 수집 항목 | 목적 |
|------|-----------|-----------|------|
| 필수 | 회원 가입(구글 로그인) | • Google UID<br>• 구글 계정 이메일<br>• 프로필 이름·사진 URL | 본인 확인, 중복 가입 방지 |
| 필수 | 서비스 이용 | • 일정 제목·내용·날짜·시간·반복 정보·완료 여부 등 일정 데이터 | 핵심 기능(일정 등록·조회·알림·공유) 제공 |
| 선택 | 친구 추가 | • 상대방 이메일 주소 | 친구 초대·공유 기능 |
| 자동 수집 | 앱 실행·사용 | • OS/단말 정보, 앱 버전, 로그·오류 기록 | 서비스 품질 개선, 불법 사용 방지 |

※ 민감정보(건강·종교·정치성향 등)는 일체 수집하지 않습니다.

---

## 2. 개인정보 수집·이용 목적

1. **서비스 제공 및 유지**: 일정 등록·수정·삭제, 알림, 친구 초대·공유 등  
2. **회원 관리**: 가입·탈퇴 처리, 문의 대응, 불량 이용자 제재  
3. **서비스 개선**: 오류 분석, 기능·UI 개선, 통계 분석  
4. **법적 의무 이행**: 관계 법령·사법기관 요청에 대한 협조

---

## 3. 보유·이용 기간 및 파기 절차

| 데이터 구분 | 보유 기간 | 파기 방법 |
|-------------|-----------|-----------|
| 회원 정보 (Google UID·이메일 등) | 회원 탈퇴 시 즉시 |  즉시 삭제 |
| **공유용 일정 중간 문서**<br>(공유 대상이 모두 수신·동기화할 때까지 유지) | 공유 완료 확인 후 **즉시 삭제**<br>(최대 30 일 이내) | 자동 삭제 스크립트로 물리적 삭제 |
| 일반 일정 데이터 | 이용자가 앱 내에서 삭제하거나, 회원 탈퇴 시 | 동일 |
| 로그·오류 기록 | 수집 후 6 개월 | 압축 후 일괄 삭제 |
| 법령 보존 데이터(근거 법령 존재 시) | 각 법령에서 정한 기간 | 기간 만료 후 즉시 파기 |

> **공유용 일정 중간 문서란?**  
> 일정 공유 기능을 사용할 때 **Firestore 서버에 임시로 등록되는 문서**로,  
> 모든 수신자가 성공적으로 동기화(수신 확인)한 것이 확인되면 자동으로 삭제됩니다.

---

## 4. 개인정보 제3자 제공

회사는 **이용자의 사전 동의 없이** 개인정보를 제3자에게 제공하지 않습니다.  
단, 법령에 의거하거나 수사기관이 영장을 제시하는 경우에 한해 제공될 수 있습니다.


> **[내부 관리자 접근 가능성 고지]**  
> 본 서비스는 Google Cloud의 **저장 시 AES‑256 암호화**(server‑side encryption)를 적용해 데이터가 디스크에는 암호화된 상태로 저장됩니다.  
> 그러나 이는 **서버‑측 암호화**이므로, 서비스 로직 또는 관리자 API 호출 시 서버가 자동으로 복호화합니다.  
> - 그 결과, **관리자 권한이 있는 경우 복호화된 일정 데이터를 평문으로 열람할 기술적 가능성**이 존재합니다.  
> - 회사는 업무와 무관한 무단 열람을 금지하며, **최소 인원 접근·로그 기록·정기 감사** 등 내부 정보보호정책으로 통제합니다.  
> - 이용자는 이러한 기술적 한계를 인지하고 서비스를 이용합니다.  
>
> **평문 열람 가능 범위**  
> - 일정 공유 기능으로 생성되는 **_공유용 일정 중간 문서_**(모든 수신자가 동기화하기 전까지 Firestore에 임시 저장되는 문서)  
> - **모든 수신자가 동기화 완료하면 중간 문서는 즉시 자동 삭제**되므로, 그 이후에는 관리자도 해당 데이터를 열람할 수 없습니다.


---

## 5. 개인정보 처리 위탁

| 수탁 업체 | 위탁 업무 | 이전 국가 | 보유·이용 기간 |
|-----------|-----------|-----------|----------------|
| Google LLC (Firebase) | • Firebase Authentication<br>• Firestore 데이터 호스팅<br>• Firebase Cloud Messaging (알림) | 미국 | 위탁 계약 종료 또는 서비스 탈퇴 시 |

※ Google Cloud는 전송 구간 TLS 및 저장 구간 AES‑256 암호화를 기본 적용합니다.

---

## 6. 이용자의 권리 및 행사 방법

1. **열람·정정·삭제**: 앱 “설정 → 개인정보 관리” 또는 고객센터 요청  
2. **처리 정지 요구**: 법이 정한 경우에 한해 요청 가능  
3. **개인정보 이동**: 기계 판독 가능한 형태(예: JSON)로 내보내기 요청 가능  
4. **대리인 권리 행사**: 위임장·신분증 사본 제출 시 가능

---

## 7. 개인정보의 안전성 확보 조치

| 구분 | 조치 내용 |
|------|-----------|
| 기술적 | • TLS(HTTPS) 암호화 통신<br>• 서버 저장 시 AES‑256 암호화<br>• 주기적 취약점 스캔·패치 |
| 관리적 | • 최소 권한 원칙, 접근 로그 1 년 보관<br>• 연 1회 이상 개인정보보호 교육 |
| 물리적 | • Google 데이터센터 출입 통제, 다중 인증 |

---

## 8. 국외 이전에 대한 정보

서비스 운영상 개인정보가 **미국** 소재 Google Cloud 서버로 전송·보관됩니다. Google Cloud는 ISO / IEC 27001 등 국제 보안 인증을 취득하고 있으며, 회사는 「개인정보 보호법」 제39조의12에 따라 국외 이전 사실을 고지합니다.

---

## 9. 아동의 개인정보 보호

서비스는 **만 14세 미만 아동을 특별히 대상으로 하지 않으며**, Google 계정 정책상 개인 Google 계정을 만들 수 있는 연령(국가별 상이, 일반적으로 만 14세 이상)에 따라 가입이 제한됩니다.  
회사는 만 14세 미만 아동의 개인정보가 수집되었음을 인지한 경우 **법정대리인의 동의를 요청하거나 즉시 삭제**합니다.

---

## 10. 쿠키·유사 기술

웹사이트가 아닌 모바일 앱 전용 서비스이므로 브라우저 쿠키를 사용하지 않습니다.

---

## 11. 개인정보 보호책임자

| 구분 | 성명 | 연락처 |
|------|------|--------|
| 개인정보 보호책임자 겸 담당자 | **윤선종** | novelwhgdk@gmail.com |

※ 문의 시 7일 이내 답변·처리해 드립니다.

---

## 12. 고지 의무 및 변경 절차

- 본 방침은 시행일로부터 적용됩니다.  
- 내용 추가·삭제·수정이 있을 경우, 변경 최소 7 일 전 앱 공지 및 본 페이지에 게시합니다.  
- 중요한 사항 변경(수집 항목·이용 목적·보유 기간 등)은 최소 30 일 전 고지합니다.

---

> © 2025 모두의 일정. 이 문서는 **CC0 1.0 Universal**로 배포되며, 누구나 자유롭게 복제·배포·개정할 수 있습니다.
