# HUAYIK Studio — ElevenLabs OAuth CIMD

Public Client ID Metadata Document for HUAYIK Studio ElevenLabs OAuth (no secrets).

## Paste this URL into Studio

Settings → บัญชีและโปรไฟล์ → ElevenLabs → ตั้งค่า OAuth เพิ่มเติม → **URL ข้อมูลแอป OAuth บน HTTPS สาธารณะ**

```
https://cdn.jsdelivr.net/gh/HuaYik/huayik-studio-elevenlabs-oauth@main/elevenlabs-client-metadata.json
```

Then click **บันทึก URL แอป**, then **ล็อกอิน / เชื่อม ElevenLabs ใหม่**.

## Checks
- HTTP 200
- Content-Type: `application/json`
- `client_id` field equals this URL exactly
- `redirect_uris` includes `http://127.0.0.1:8876/oauth/elevenlabs/callback/` (trailing slash)

Repo: https://github.com/HuaYik/huayik-studio-elevenlabs-oauth
