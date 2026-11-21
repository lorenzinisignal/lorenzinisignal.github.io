---
title: "데일리 마켓 브리핑: 2026년 11월 21일 (주간 결산)"
date: 2026-11-21 11:00:00 +0900
categories: [Finance, Market]
tags: [market-briefing, nasdaq100, treasury, kospi, nvidia, anthropic]
---

미국·한국 11월 20일 종가 기준으로 5대 감시지표(나스닥100 선행 PER, 미국 10년물 금리, WTI, BEI, CNN 공포·탐욕 지수)와 주간 흐름을 정리했습니다. AI주 매도가 확산되며 S&P 500과 다우는 조정장에 진입했고, 나스닥 종합지수는 연초 대비 마이너스로 돌아섰습니다.

<style>
.mwb { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #fff; color: #111; font-size: 14px; padding: 16px; border-radius: 12px; border: 1px solid #eee; margin: 1rem 0; }
.mwb * { box-sizing: border-box; }
.mwb .meta { font-size: 11px; color: #999; letter-spacing: 0.04em; text-transform: uppercase; margin-bottom: 3px; }
.mwb .phase { font-size: 11px; color: #bbb; margin-bottom: 16px; }
.mwb .event-banner { border-radius: 12px; padding: 14px 16px; margin-bottom: 12px; background: linear-gradient(135deg, #140808 0%, #7a1c1c 100%); color: #f1e2e2; }
.mwb .wb-eyebrow { font-size: 10px; color: #d6a8a8; letter-spacing: 0.06em; text-transform: uppercase; margin-bottom: 6px; }
.mwb .wb-title { font-size: 15px; font-weight: 700; margin-bottom: 8px; color: #fff8f8; }
.mwb .wb-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 8px; margin-top: 10px; }
.mwb .wb-item { background: rgba(255,255,255,0.08); border-radius: 8px; padding: 8px 10px; }
.mwb .wb-item-label { font-size: 10px; color: #d6a8a8; margin-bottom: 3px; }
.mwb .wb-item-val { font-size: 13px; font-weight: 600; color: #fff; }
.mwb .sec { font-size: 11px; color: #999; letter-spacing: 0.04em; margin: 4px 0 6px; }
.mwb .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(145px,1fr)); gap: 10px; margin-bottom: 12px; }
.mwb .card { background: #f7f7f5; border-radius: 10px; padding: 14px; border: none; }
.mwb .lbl { font-size: 11px; color: #777; margin-bottom: 7px; }
.mwb .val { font-size: 21px; font-weight: 500; margin-bottom: 6px; line-height: 1.1; color: #111; }
.mwb .badge { display: inline-block; font-size: 11px; padding: 2px 9px; border-radius: 20px; font-weight: 500; margin-bottom: 6px; }
.mwb .ba { background: #FDF0DC; color: #8A5000; }
.mwb .br { background: #FDECEA; color: #922B2B; }
.mwb .bg { background: #E5F4EC; color: #1A6A3A; }
.mwb .sub { font-size: 11px; color: #999; line-height: 1.55; }
.mwb .chip { display: inline-flex; font-size: 11px; padding: 1px 6px; border-radius: 4px; margin-left: 4px; font-weight: 500; vertical-align: middle; }
.mwb .cu { background: #FDECEA; color: #922B2B; }
.mwb .cd { background: #E5F4EC; color: #1A6A3A; }
.mwb .cn { background: #f0f0ee; color: #555; }
.mwb .week-bar { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 12px; }
.mwb .wb2 { flex: 1; min-width: 90px; background: #f7f7f5; border-radius: 10px; padding: 10px 12px; text-align: center; }
.mwb .wb2-name { font-size: 10px; color: #888; margin-bottom: 4px; }
.mwb .wb2-val { font-size: 15px; font-weight: 600; color: #111; }
.mwb .wb2-sub { font-size: 11px; margin-top: 2px; }
.mwb .pos { color: #1a7a4a; }
.mwb .neg { color: #c0392b; }
.mwb .amb { color: #8A5000; }
.mwb .mom { border: 1px solid #eee; border-radius: 12px; padding: 12px 14px; margin-bottom: 12px; }
.mwb .mom-t { font-size: 12px; font-weight: 600; margin-bottom: 8px; color: #111; }
.mwb .mom-row { display: flex; justify-content: space-between; gap: 8px; font-size: 12px; padding: 5px 0; border-bottom: 1px dashed #eee; color: #111; }
.mwb .mom-row:last-child { border-bottom: none; }
.mwb .al { border-left: 3px solid; border-radius: 8px; padding: 10px 14px; margin-bottom: 10px; font-size: 12px; line-height: 1.65; }
.mwb .al-r { border-left-color: #dc2626; background: #fef2f2; color: #7f1d1d; }
.mwb .al-a { border-left-color: #d97706; background: #fffbeb; color: #78350f; }
.mwb .al-b { border-left-color: #2563eb; background: #eff6ff; color: #1e3a8a; }
.mwb .al-g { border-left-color: #16a34a; background: #f0fdf4; color: #14532d; }
.mwb .panel { border: 1px solid #eee; border-radius: 12px; padding: 14px 16px; }
.mwb .pt { font-size: 13px; font-weight: 600; margin-bottom: 12px; color: #111; }
.mwb .row { display: flex; gap: 10px; align-items: flex-start; margin: 0 0 9px 0; font-size: 13px; line-height: 1.5; color: #111; }
.mwb .row:last-child { margin-bottom: 0; }
.mwb .dot { width: 7px; height: 7px; border-radius: 50%; margin-top: 5px; flex-shrink: 0; }
.mwb .muted { color: #777; }
.mwb .footer { font-size: 11px; color: #bbb; text-align: right; margin-top: 10px; line-height: 1.5; }
</style>

<div class="mwb">
<div class="meta">Daily Briefing &nbsp;·&nbsp; 2026년 11월 21일 토요일 &nbsp;·&nbsp; 주간 결산 · 11/20 종가 기준</div>
<div class="phase">Phase 1 · Capital Gain · Nasdaq-Heavy</div>
<div class="event-banner">
<div class="wb-eyebrow">🩸 검은 금요일 (11/20)</div>
<div class="wb-title">S&amp;P·다우 조정장 진입 · 나스닥 −5.3%로 연초 대비 마이너스 전환</div>
<div style="font-size:12px; color:#ecd0d0; line-height:1.6;">S&amp;P 500 7일 연속 하락, 주간 −8.6% (2025년 4월 이후 최악). 나스닥100은 장중 약세장(−20%) 진입.<br>엔비디아 −14% (SEC 회계 검토 보도 + 캘리포니아 AG 대중국 칩 소환장). 메모리·AI 인프라주 일제히 −12~16%.</div>
<div class="wb-grid">
<div class="wb-item"><div class="wb-item-label">VIX</div><div class="wb-item-val" style="color:#fca5a5;">35.9 (+26%)</div></div>
<div class="wb-item"><div class="wb-item-label">CNN 공포·탐욕</div><div class="wb-item-val" style="color:#fca5a5;">14 · 3월 이후 최저</div></div>
<div class="wb-item"><div class="wb-item-label">12월 25bp 인상</div><div class="wb-item-val">~90%</div></div>
</div>
</div>
<div class="sec">11/20 마감 · (주간)</div>
<div class="week-bar">
<div class="wb2"><div class="wb2-name">S&amp;P 500</div><div class="wb2-val">6,910</div><div class="wb2-sub neg">−3.7% (주 −8.6%)</div></div>
<div class="wb2"><div class="wb2-name">Nasdaq</div><div class="wb2-val">22,618</div><div class="wb2-sub neg">−5.3% (주 −10%)</div></div>
<div class="wb2"><div class="wb2-name">Nasdaq-100</div><div class="wb2-val">25,029</div><div class="wb2-sub neg">−5.6% · 장중 약세장</div></div>
<div class="wb2"><div class="wb2-name">KOSPI</div><div class="wb2-val">4,870</div><div class="wb2-sub neg">−5.21% · 매도 사이드카</div></div>
<div class="wb2"><div class="wb2-name">금 현물</div><div class="wb2-val">~$3,515</div><div class="wb2-sub neg">−4.6% · 14.5개월 최저</div></div>
</div>
<div class="grid">
<div class="card"><div class="lbl">① Nasdaq 100 Fwd PER</div><div class="val">≈21~22x <span class="chip cd">▼ 23.6→</span></div><span class="badge bg">고평가 해소 진행</span><div class="sub">11월 월간치 23.6x에 주간 −10% 반영 추정<br>2년 평균(25.4x) 대비 큰 폭 할인</div></div>
<div class="card"><div class="lbl">② 미국 10년물 금리</div><div class="val">4.92% <span class="chip cd">▼ 12bp</span></div><span class="badge ba">5% 하회 · 안전자산 수요</span><div class="sub">5일 연속 하락, 10/22 이후 최대 낙폭<br>2Y 4.63% · 금리 완화가 아닌 <b>도피성 매수</b></div></div>
<div class="card"><div class="lbl">③ WTI 원유</div><div class="val">$83.98 <span class="chip cn">▲ 0.9%</span></div><span class="badge bg">3주 연속 하락</span><div class="sub">주간 −5.2% · 공급 과잉 우려<br>후티 리야드 공격 등 중동 리스크는 상존</div></div>
<div class="card"><div class="lbl">④ BEI 10년 (기대인플레)</div><div class="val">≈2.1% <span class="chip cn">11/19</span></div><span class="badge bg">안정</span><div class="sub">11/19 산출(10Y 5.05% − TIPS 2.90%)<br>유가 하락 지속 → 하방 압력</div></div>
<div class="card"><div class="lbl">⑤ CNN 공포·탐욕 지수</div><div class="val">14 <span class="chip cu">▼ 19→14</span></div><span class="badge br">극단적 공포</span><div class="sub">8일간 −26pt 급락, 3/30 이후 최저<br>봄 패닉 저점(~10)에 근접</div></div>
</div>
<div class="mom">
<div class="mom-t">⚖ 듀얼 모멘텀 체크 (11/20 종가)</div>
<div class="mom-row"><span>Nasdaq 종합 연초 대비</span><span class="neg"><b>−2.7%</b></span></div>
<div class="mom-row"><span>Nasdaq 종합 12개월 (추정)</span><span class="amb"><b>+2% 내외 · 0선 근접</b></span></div>
<div class="mom-row"><span>KOSPI 12개월 (추정)</span><span class="pos"><b>+20%대</b></span></div>
<div class="mom-row"><span>절대 모멘텀 (Nasdaq)</span><span class="neg"><b>음전환 임박 · 3대 지수 200일선 하회</b></span></div>
<div class="mom-row"><span>상대 모멘텀 (12M 기준)</span><span class="amb"><b>KOSPI 우위, 격차 축소</b></span></div>
</div>
<div class="al al-r">⚠ <strong>엔비디아 = 이번 하락의 진앙.</strong> 7거래일 연속 하락, 하루 −14%로 $125.53. Reuters 보도로 SEC가 회계 문제를 검토 중이고, 캘리포니아 AG는 칩의 중국 유입 여부로 소환장을 발부했습니다. CEO 사임(11/12) → 실적 호조 무반응 → 규제·회계 리스크로 이어지는 3단계 신뢰 훼손이 AI 밸류체인 전체(메모리·네트워크·전력)로 번지는 중입니다.</div>
<div class="al al-b">🤖 <strong>앤트로픽(ANT) 상장 2일차 −8.5%.</strong> $88.91로 공모가 $83 대비 +7.1%만 남겼습니다(장중 $83.05까지 하락). 대형 IPO 재원이 기존 AI 보유분 매도로 마련되는 '수급 흡수' 우려가 현실화됐고, SPY에서만 하루 $11.65B가 빠져나갔습니다.</div>
<div class="al al-a">🏛 <strong>금리는 내렸지만 연준은 여전히 매파.</strong> 10년물 4.92%(5% 하회)는 안전자산 도피의 결과입니다. 연준 인사는 오히려 매파적입니다. Paulson은 "연속 인상에 열려 있다", Cook은 "늦으면 뒤처진다"고 했습니다. 12/9 FOMC 25bp 인상 확률 ~90%, 50bp 확률은 크게 줄었습니다. 현 기준금리 3.75~4.00%.</div>
<div class="al al-g">🇰🇷 <strong>KOSPI −5.21%, 종가 4,800선은 1월 이후 처음.</strong> 외국인 1조 2,682억원 순매도(6거래일 연속), 코스피·코스닥 동시 매도 사이드카. 대만 TAIEX 주간 −17.5%(사상 최대), 닛케이 −5%. KOSPI도 반도체 비중이 높아 나스닥 AI 리스크와 동조화되면서, 분산 효과가 약해진 국면입니다.</div>
<div class="panel">
<div class="pt">다음 주 체크포인트</div>
<div class="row"><div class="dot" style="background:#c0392b;"></div><div><span class="muted">신호 충돌: F&amp;G 14 · VIX 36 · 주간 −8.6%는 2025년 4월 저점과 닮은 극단값이지만, 절대 모멘텀은 음전환 직전입니다. 월중 감정적 대응보다 12/1 월간 리밸런싱 규칙으로 판단합니다.</span></div></div>
<div class="row"><div class="dot" style="background:#e67e22;"></div><div><span class="muted">① 엔비디아 SEC 후속 보도 ② ANT 3일차 옵션 상장 후 수급 ③ 외국인 KOSPI 매도 7일째 여부 ④ 11/26 추수감사절 휴장·27일 조기마감 ⑤ 11/29 OPEC+ ⑥ 12/1 월간 리밸런싱</span></div></div>
</div>
<div class="footer">데이터 기준: 美·韓 2026-11-20 종가 · ≈ 표시는 추정치 (Fwd PER·12M 모멘텀 추정, BEI는 11/19 TIPS 기준 산출)<br>투자 권유가 아닌 개인 기록입니다</div>
</div>

## 출처

- [AP via Yakima Herald: How major US stock indexes fared Friday 11/20/2026](https://www.yakimaherald.com/news/nation_and_world/business/how-major-us-stock-indexes-fared-friday-11-20-2026/article_963ce6d2-85a3-5fd6-981d-e60b72a58fbb.html)
- [Capp Notes: Closing Look — Friday, November 20, 2026](https://cappnotes.substack.com/p/closing-look-friday-november-20-2026)
- [Rallies.ai: Treasury yields fall for day and week as AI trade concerns spur safe-haven bid](https://rallies.ai/news/treasury-yields-fall-for-day-and-week-as-ai-trade-concerns-spur-safe-haven-bid-ba86e7c888e22750)
- [EnergyNow: WTI Closes at $83.98, Brent at $92.57](https://energynow.com/2026/11/oil-prices-rebound-friday-on-middle-east-tensions-but-fall-for-third-straight-week-wti-closes-at-83-98-brent-at-92-57/)
- [Cryptonews: Fear & Greed Index falls to 14](https://cryptonews.net/news/analytics/33785428/)
- [MacroMicro: NASDAQ 100 Forward PE](https://en.macromicro.me/series/23955/nasdaq-100-pe)
- [Trading Economics: US 10 Year Treasury / TIPS](https://tradingeconomics.com/united-states/government-bond-yield)
- [한국경제: 코스피 4869 마감…외국인 1조2682억원 순매도](https://www.hankyung.com/article/202611200429i)
