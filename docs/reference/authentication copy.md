---
title: Authentication2
category:
  uri: reference
slug: authentication2
position: 2
---
test10


> 모든 엔드포인트는 인증이 필요하며, 표준 Bearer 토큰 기반을 사용합니다.

## Overview
- **방식**: Bearer 토큰 (API Key 또는 OAuth2 토큰)
- **헤더**: `Authorization: Bearer <token>`
- **전송**: HTTPS 필수

요청 헤더 예시:
```http
Authorization: Bearer YOUR_API_KEY
Content-Type: application/json