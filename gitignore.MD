# ── Node / 프론트 개발 산출물 ──
node_modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*
package-lock.json
pnpm-lock.yaml
coverage/
.vite/
.eslintcache
.turbo/

# ── 정적 사이트 빌드 산출물 (GitHub Pages 루트 배포 시 불필요) ──
dist/
build/
out/
public/out/

# ── OS / 에디터 ──
.DS_Store
Thumbs.db
desktop.ini
.idea/
.vscode/
*.swp
*.swo
*.swn

# ── 로컬 임시 / 백업 파일 ──
*.bak
*.orig
*.rej
*.log
*.tmp
*~
*.html.bak
backup_*.html
index_*.html.bak

# ── 환경변수 / 인증 ──
.env
.env.*
!.env.example
*.pem
*.key
.credentials
.netrc

# ── 워크스페이스 캐시 (개발 도구) ──
.arena/
.cache/
.mypy_cache/
.pytest_cache/
.ruff_cache/
.nox/
.parcel-cache/
.svelte-kit/
__pycache__/