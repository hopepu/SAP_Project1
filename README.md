# SAP CAP 첫 프로젝트

2025년 1월, SAP BTP 학습을 시작하며 만든 **CAP(Cloud Application Programming Model) 기본 프로젝트**입니다.

- `cds init`으로 생성한 CAP Node.js 프로젝트 구조
- HANA HDI 컨테이너에 배포하기 위한 `mta.yaml` (srv 모듈 + db-deployer 모듈)
- CI/CD 파이프라인 설정(`Jenkinsfile`, `.pipeline`)

## 프로젝트 구조
| 폴더/파일 | 역할 |
|---|---|
| `db/` | 도메인 모델(CDS)과 데이터 |
| `srv/` | 서비스 정의와 핸들러 |
| `mta.yaml` | Cloud Foundry 배포 디스크립터 |

## 실행
```bash
npm install
cds watch
```

---

이 프로젝트에서 출발해 현재는 실무 SAP BTP 포털을 개발하고 있습니다. → [sap-btp-portfolio](https://github.com/hopepu/sap-btp-portfolio)
