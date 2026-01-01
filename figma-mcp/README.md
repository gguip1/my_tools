# Claude Figma MCP

Claude Code에서 Figma API를 사용하기 위한 MCP 설정

## 설정

```bash
cp .mcp.json.example .mcp.json
```

`.mcp.json` 열어서 `YOUR_FIGMA_API_KEY` 부분을 실제 키로 교체

## Figma API 키 발급

1. https://www.figma.com/developers/api#access-tokens 접속
2. Figma 로그인
3. "Generate new token" 클릭
4. 토큰 이름 입력 후 생성
5. 발급된 키를 `.mcp.json`에 입력

## 기능

- Figma 파일 디자인 정보 조회
- 레이아웃 및 스타일 정보 추출
- 컴포넌트 구조 분석
