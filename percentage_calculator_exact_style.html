<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Percentage Calculator</title>

  <style>
    * {
      box-sizing: border-box;
    }

    :root {
      --bg: #05090f;
      --text: #d8dbe2;
      --muted: #a7abb4;
      --tile-text: #050607;
      --red: #ff5757;
      --orange: #ff8426;
      --green: #83d65b;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: "Avenir Next", "Segoe UI", Arial, sans-serif;
      background:
        radial-gradient(circle at top center, rgba(255,255,255,0.07), transparent 30%),
        radial-gradient(circle at 20% 45%, rgba(255,82,82,0.08), transparent 28%),
        radial-gradient(circle at 78% 48%, rgba(110,232,79,0.08), transparent 30%),
        linear-gradient(180deg, #0b1117, #05080c);
      color: var(--text);
      padding: 20px 22px;
    }

    .page {
      width: 100%;
      max-width: 1440px;
      margin: 0 auto;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: clamp(58px, 7vw, 98px);
      line-height: 0.95;
      font-weight: 200;
      letter-spacing: -4px;
      background: linear-gradient(90deg, #ff5b5b 0%, #ff9f43 36%, #d7d961 58%, #79c85b 100%);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      filter: saturate(0.78);
    }

    .subtitle {
      margin: 26px 0 28px;
      color: #b8bbc3;
      font-size: clamp(18px, 2vw, 27px);
      font-weight: 200;
      letter-spacing: 0.2px;
    }

    .input-label {
      color: #c8cbd3;
      font-size: 21px;
      text-transform: uppercase;
      letter-spacing: 0.6px;
      margin-bottom: 14px;
      font-weight: 200;
    }

    .input-wrap {
      width: 300px;
      height: 82px;
      margin: 0 auto 30px;
      border: 1px solid rgba(255,255,255,0.28);
      border-radius: 16px;
      background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.015));
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      box-shadow:
        inset 0 0 18px rgba(255,255,255,0.025),
        0 10px 30px rgba(0,0,0,0.18);
    }

    .input-wrap::after {
      content: "";
      width: 2px;
      height: 46px;
      border-radius: 999px;
      background: linear-gradient(180deg, transparent, rgba(255,255,255,0.36), transparent);
      position: absolute;
      right: 72px;
      top: 50%;
      transform: translateY(-50%);
    }

    input {
      width: 100%;
      height: 100%;
      border: none;
      outline: none;
      background: transparent;
      color: #f1f5f9;
      text-align: center;
      font-size: 36px;
      font-weight: 300;
      font-family: "Avenir Next", "Segoe UI", Arial, sans-serif;
      padding: 0 60px 0 20px;
    }

    input::placeholder {
      color: rgba(255,255,255,0.32);
    }

    .stepper {
      position: absolute;
      right: 18px;
      top: 50%;
      transform: translateY(-50%);
      display: flex;
      flex-direction: column;
      gap: 8px;
      z-index: 5;
    }

    .step-btn {
      width: 28px;
      height: 20px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,0.12);
      background: rgba(255,255,255,0.055);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: 0.15s ease;
    }

    .step-btn:hover {
      background: rgba(255,255,255,0.12);
    }

    .step-btn svg {
      width: 11px;
      height: 11px;
      stroke: rgba(255,255,255,0.72);
      stroke-width: 2.2;
      fill: none;
      stroke-linecap: round;
      stroke-linejoin: round;
    }

    .dashboard {
      display: grid;
      grid-template-columns: 0.9fr 1.85fr;
      gap: 18px;
      align-items: stretch;
      text-align: left;
    }

    .section {
      border-radius: 18px;
      background: rgba(8, 13, 17, 0.78);
      padding: 20px;
      min-height: 420px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .stops-section {
      border: 1px solid rgba(255, 100, 55, 0.62);
      box-shadow: 0 0 0 1px rgba(255, 100, 55, 0.08);
    }

    .limits-section {
      border: 1px solid rgba(113, 220, 106, 0.42);
      box-shadow: 0 0 0 1px rgba(113, 220, 106, 0.06);
    }

    .section-header {
      display: flex;
      align-items: center;
      gap: 26px;
      margin-bottom: 20px;
    }

    .icon {
      width: 72px;
      height: 72px;
      border-radius: 14px;
      border: 1px solid rgba(255,255,255,0.14);
      background: linear-gradient(180deg, rgba(255,255,255,0.075), rgba(255,255,255,0.025));
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: inset 0 0 20px rgba(255,255,255,0.035);
      flex-shrink: 0;
    }

    .icon svg {
      width: 46px;
      height: 46px;
      stroke-width: 2.3;
      stroke-linecap: round;
      stroke-linejoin: round;
      fill: none;
    }

    .stops-section .icon svg {
      stroke: #ff5b5b;
      filter: drop-shadow(0 0 8px rgba(255, 82, 82, 0.22));
    }

    .limits-section .icon svg {
      stroke: #83e35d;
      filter: drop-shadow(0 0 8px rgba(131, 227, 93, 0.22));
    }

    .section-title {
      margin: 0;
      font-size: 42px;
      line-height: 1;
      letter-spacing: -0.5px;
      font-weight: 300;
      text-transform: uppercase;
    }

    .stops-section .section-title {
      color: #ff6363;
    }

    .limits-section .section-title {
      color: #9be36e;
    }

    .section-subtitle {
      margin-top: 12px;
      font-size: 20px;
      color: #d8d8de;
      font-weight: 300;
    }

    .tiles {
      display: grid;
      gap: 12px;
    }

    .stops-tiles {
      grid-template-columns: repeat(2, 1fr);
    }

    .limits-tiles {
      grid-template-columns: repeat(5, 1fr);
    }

    .tile {
      min-height: 260px;
      border-radius: 14px;
      padding: 18px 14px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      position: relative;
      box-shadow: inset 0 0 34px rgba(255,255,255,0.12);
    }

    .tile::after {
      content: "";
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      height: 10px;
      opacity: 0.95;
    }

    .stop-75 {
      background: linear-gradient(160deg, #f29a52, #be5a1b);
      border: 1px solid rgba(255, 157, 73, 0.75);
    }

    .stop-75::after {
      background: #ff771f;
    }

    .stop-70 {
      background: linear-gradient(160deg, #e77278, #b2373e);
      border: 1px solid rgba(255, 114, 114, 0.75);
    }

    .stop-70::after {
      background: #ff4f57;
    }

    .limit-20 {
      background: linear-gradient(160deg, #d6ecca, #b6d9a6);
      border: 1px solid rgba(210, 255, 190, 0.55);
    }

    .limit-20::after {
      background: #b9ec9b;
    }

    .limit-35 {
      background: linear-gradient(160deg, #c4e3ae, #95c978);
      border: 1px solid rgba(190, 245, 155, 0.5);
    }

    .limit-35::after {
      background: #8bd85a;
    }

    .limit-50 {
      background: linear-gradient(160deg, #91c76d, #5aaa3d);
      border: 1px solid rgba(146, 224, 103, 0.5);
    }

    .limit-50::after {
      background: #64d83c;
    }

    .limit-75 {
      background: linear-gradient(160deg, #67b74a, #398e2e);
      border: 1px solid rgba(105, 210, 72, 0.5);
    }

    .limit-75::after {
      background: #4fd92e;
    }

    .limit-100 {
      background: linear-gradient(160deg, #4e9e3f, #2d742b);
      border: 1px solid rgba(92, 195, 75, 0.5);
    }

    .limit-100::after {
      background: #3fc128;
    }

    .percent {
      color: var(--tile-text);
      font-size: clamp(47px, 4.3vw, 72px);
      line-height: 0.9;
      font-weight: 300;
      letter-spacing: -5px;
      text-align: center;
    }

    .percent .small {
      font-size: 0.45em;
      letter-spacing: -2px;
      margin-left: 2px;
      font-weight: 100;
    }

    .dash {
      width: 82%;
      border-top: 1.5px dashed rgba(255,255,255,0.72);
      margin: 24px 0 20px;
    }

    .value {
      color: var(--tile-text);
      font-size: clamp(24px, 2.4vw, 35px);
      line-height: 1;
      font-weight: 700;
      letter-spacing: -1px;
      text-align: center;
      white-space: nowrap;
    }

    .footer-note {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 18px;
      margin-top: 22px;
      color: #aeb2bc;
      font-size: 22px;
      text-align: center;
      font-weight: 300;
    }

    .info {
      width: 44px;
      height: 44px;
      border-radius: 50%;
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(131, 227, 93, 0.8);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #d4d4d8;
      flex-shrink: 0;
      box-shadow: inset 0 0 14px rgba(255,255,255,0.025);
    }

    .info svg {
      width: 24px;
      height: 24px;
      stroke: #9be36e;
      stroke-width: 1.8;
      fill: none;
      stroke-linecap: round;
      stroke-linejoin: round;
    }

    @media (max-width: 1180px) {
      .dashboard {
        grid-template-columns: 1fr;
      }

      .section {
        min-height: auto;
      }
    }

    @media (max-width: 900px) {
      body {
        padding: 28px 18px;
      }

      .limits-tiles {
        grid-template-columns: repeat(2, 1fr);
      }

      .tile {
        min-height: 290px;
      }
    }

    @media (max-width: 560px) {
      h1 {
        font-size: 48px;
        letter-spacing: -2px;
      }

      .subtitle {
        font-size: 18px;
        margin: 34px 0 36px;
      }

      .input-wrap {
        width: 100%;
      }

      .section {
        padding: 22px;
      }

      .section-header {
        gap: 16px;
      }

      .icon {
        width: 66px;
        height: 66px;
      }

      .icon svg {
        width: 44px;
        height: 44px;
      }

      .section-title {
        font-size: 34px;
      }

      .section-subtitle {
        font-size: 20px;
      }

      .stops-tiles,
      .limits-tiles {
        grid-template-columns: 1fr;
      }

      .footer-note {
        font-size: 16px;
        align-items: flex-start;
      }
    }
  </style>
</head>

<body>
  <main class="page">
    <h1>Percentage Calculator</h1>
    <div class="subtitle">Enter a number to calculate risk tiers and profit targets</div>

    <div class="input-label">Enter Number</div>
    <div class="input-wrap">
      <input id="mainNumber" type="text" inputmode="decimal" pattern="[0-9]*[.]?[0-9]*" placeholder="0" autofocus />
      <div class="stepper">
        <div class="step-btn" onclick="stepValue(1)">
          <svg viewBox="0 0 24 24">
            <path d="M6 14l6-6 6 6"></path>
          </svg>
        </div>
        <div class="step-btn" onclick="stepValue(-1)">
          <svg viewBox="0 0 24 24">
            <path d="M6 10l6 6 6-6"></path>
          </svg>
        </div>
      </div>
    </div>

    <section class="dashboard">
      <div class="section stops-section">
        <div>
          <div class="section-header">
            <div class="icon" aria-hidden="true">
              <svg viewBox="0 0 64 64">
                <path d="M32 10v40"></path>
                <path d="M14 34l18 18 18-18"></path>
              </svg>
            </div>
            <div>
              <div class="section-title">Stops</div>
              <div class="section-subtitle">Risk Tiers</div>
            </div>
          </div>

          <div class="tiles stops-tiles">
            <div class="tile stop-75">
              <div class="percent">75<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="stop75">-</div>
            </div>

            <div class="tile stop-70">
              <div class="percent">70<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="stop70">-</div>
            </div>
          </div>
        </div>
      </div>

      <div class="section limits-section">
        <div>
          <div class="section-header">
            <div class="icon" aria-hidden="true">
              <svg viewBox="0 0 64 64">
                <path d="M32 54V14"></path>
                <path d="M14 30l18-18 18 18"></path>
              </svg>
            </div>
            <div>
              <div class="section-title">Limits</div>
              <div class="section-subtitle">Profit Targets</div>
            </div>
          </div>

          <div class="tiles limits-tiles">
            <div class="tile limit-20">
              <div class="percent">20<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="limit20">-</div>
            </div>

            <div class="tile limit-35">
              <div class="percent">35<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="limit35">-</div>
            </div>

            <div class="tile limit-50">
              <div class="percent">50<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="limit50">-</div>
            </div>

            <div class="tile limit-75">
              <div class="percent">75<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="limit75">-</div>
            </div>

            <div class="tile limit-100">
              <div class="percent">100<span class="small">%</span></div>
              <div class="dash"></div>
              <div class="value" id="limit100">-</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="footer-note">
      <div class="info" aria-hidden="true">
        <svg viewBox="0 0 24 24">
          <circle cx="12" cy="12" r="9"></circle>
          <path d="M12 10v6"></path>
          <path d="M12 7h.01"></path>
        </svg>
      </div>
      <div>All Limits have a plus 2 added to the formula to account for broker fees.</div>
    </div>
  </main>

  <script>
    const input = document.getElementById("mainNumber");

    input.addEventListener("input", calculate);
    input.addEventListener("keyup", calculate);
    input.addEventListener("change", calculate);

    function getCleanNumber() {
      const cleaned = input.value.replace(/,/g, ".").replace(/[^0-9.\-]/g, "");
      return {
        raw: cleaned,
        number: Number(cleaned)
      };
    }

    function stepValue(direction) {
      const parsed = getCleanNumber();
      const current = parsed.raw === "" || isNaN(parsed.number) ? 0 : parsed.number;
      input.value = current + direction;
      calculate();
    }

    function formatNumber(value) {
      return value.toLocaleString(undefined, {
        minimumFractionDigits: 2,
        maximumFractionDigits: 2
      });
    }

    function setValue(id, value) {
      document.getElementById(id).textContent = formatNumber(value);
    }

    function resetValues() {
      ["stop75", "stop70", "limit20", "limit35", "limit50", "limit75", "limit100"].forEach(function(id) {
        document.getElementById(id).textContent = "-";
      });
    }

    function calculate() {
      const parsed = getCleanNumber();
      const raw = parsed.raw;
      const number = parsed.number;

      if (raw === "" || isNaN(number)) {
        resetValues();
        return;
      }

      setValue("stop75", number * 0.75);
      setValue("stop70", number * 0.70);

      setValue("limit20", (number * 1.20) + 2);
      setValue("limit35", (number * 1.35) + 2);
      setValue("limit50", (number * 1.50) + 2);
      setValue("limit75", (number * 1.75) + 2);
      setValue("limit100", (number * 2.00) + 2);
    }
  </script>
</body>
</html>
