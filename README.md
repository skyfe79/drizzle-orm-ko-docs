## 🚀 프로젝트 구조

MDX 파일은 다음 폴더에 위치합니다:

```text
├── src/
│   ├── content/
│   │   └── docs
```

공지사항 마크다운 파일:

```text
├── src/
│   ├──data/
│   │   └── announcements
```

로드맵 마크다운 파일:

```text
├── src/
│   ├──data/
│   │   └── roadmap.md
```

배송 섹션 YAML 파일:

```text
├── src/
│   ├──data/
│   │   └── shipping.yaml
```

```yaml
progress: number
weeks:
  - date:
      start: "YYYY-MM-DD"
    details:
      - string
```


## 🧞 커맨드

모든 커맨드는 프로젝트 루트 디렉토리에서 터미널을 통해 실행할 수 있습니다:

| 커맨드                   | 동작                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | 의존성 패키지 설치                            |
| `pnpm run dev`             | 로컬 개발 서버를 `localhost:4321`에서 실행      |
| `pnpm run build`           | 프로덕션 사이트를 `./dist/`에 빌드          |
| `pnpm run preview`         | 배포 전에 로컬에서 빌드 결과 미리보기     |
| `pnpm run astro ...`       | `astro add`, `astro check` 같은 CLI 커맨드 실행 |
| `pnpm run astro -- --help` | Astro CLI 사용법 확인                     |


