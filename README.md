# WELEV ARENA — 경찰특공대 협동 웹 FPS

브라우저에서 바로 하는 경찰특공대 총싸움 체험판이에요.

- 게임은 `index.html` 파일 하나로 돌아가요 (three.js, supabase-js는 CDN에서 불러와요).
- `models/`·`guns/`는 캐릭터·총 3D 모델(glb를 base64로 담은 json)이에요.
- 같이하기(무한 작전)는 Supabase(welev-games) Realtime으로 입장·연결 신호를 주고받고, 움직임·사격은 대원끼리 WebRTC로 직접 주고받아요.
- Vercel에서 이 저장소를 가져오면 별도 설정 없이 배포돼요. 프레임워크는 "Other".
