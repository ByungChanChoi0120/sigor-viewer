---
title: HTML 블록 킷
summary: 글 쓸 때 바로 복붙하는 UI 블록 모음
date: '2026-03-18'
category: lessons
tags: [html, components, blocks]
draft: true
---

글 안에서 이런 식으로 복붙해서 쓰면 돼.

## 1) 숫자 카드

```html
<div style="display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px;margin:14px 0;">
  <div style="padding:14px;border:1px solid #e4e4e7;border-radius:12px;background:#fff;text-align:center;">
    <div style="font-size:24px;font-weight:800;">522</div>
    <div style="font-size:13px;color:#71717a;">문자 발송</div>
  </div>
  <div style="padding:14px;border:1px solid #e4e4e7;border-radius:12px;background:#fff;text-align:center;">
    <div style="font-size:24px;font-weight:800;">4</div>
    <div style="font-size:13px;color:#71717a;">장표 수정</div>
  </div>
  <div style="padding:14px;border:1px solid #e4e4e7;border-radius:12px;background:#fff;text-align:center;">
    <div style="font-size:24px;font-weight:800;">40%</div>
    <div style="font-size:13px;color:#71717a;">토큰 절감</div>
  </div>
</div>
```

## 2) 타임라인

```html
<div style="margin:16px 0;padding-left:18px;border-left:2px solid #e4e4e7;">
  <div style="padding:8px 0 8px 16px;position:relative;">
    <span style="position:absolute;left:-23px;top:14px;width:10px;height:10px;border-radius:50%;background:#3b82f6;border:2px solid #fff;display:inline-block;"></span>
    <b style="font-size:13px;color:#3b82f6;">14:00</b> OpenClaw 수업 초안 작업
  </div>
  <div style="padding:8px 0 8px 16px;position:relative;">
    <span style="position:absolute;left:-23px;top:14px;width:10px;height:10px;border-radius:50%;background:#d4d4d8;border:2px solid #fff;display:inline-block;"></span>
    <b style="font-size:13px;color:#3b82f6;">15:00</b> 모집 문자 522통 발송
  </div>
</div>
```

## 3) Before / After

```html
<div style="display:grid;grid-template-columns:1fr auto 1fr;align-items:center;gap:10px;margin:14px 0;">
  <div style="padding:14px;border-radius:12px;border:1px solid #fecaca;background:#fef2f2;">
    <div style="font-size:11px;font-weight:800;color:#71717a;">BEFORE</div>
    <p style="margin:6px 0 0;">도구 하나 실패하면 작업 중단</p>
  </div>
  <div style="font-size:22px;color:#d4d4d8;">→</div>
  <div style="padding:14px;border-radius:12px;border:1px solid #bbf7d0;background:#f0fdf4;">
    <div style="font-size:11px;font-weight:800;color:#71717a;">AFTER</div>
    <p style="margin:6px 0 0;">우회 루트 + 병렬 처리 + 복구력 확보</p>
  </div>
</div>
```

## 4) 콜아웃

```html
<div style="border-radius:12px;padding:14px;margin:14px 0;border:1px solid #bfdbfe;background:#eff6ff;">
  <div style="font-size:14px;font-weight:700;margin-bottom:6px;">💡 포인트</div>
  <div style="font-size:15px;line-height:1.7;color:#3f3f46;">
    설명할 때는 문장만 쓰지 말고 숫자, 대비, 한 줄 요약을 같이 넣자.
  </div>
</div>
```
