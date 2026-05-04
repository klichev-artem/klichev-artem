<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rizza</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      background: #f7f5ef;
      color: #1f1f1f;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
    }

    main {
      min-height: 100vh;
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 64px;
      padding: 80px;
    }

    .content {
      max-width: 680px;
      align-self: center;
    }

    .mark {
      font-size: 14px;
      letter-spacing: 0.24em;
      color: #777;
      margin-bottom: 72px;
    }

    h1 {
      font-size: clamp(48px, 8vw, 112px);
      font-weight: 400;
      line-height: 0.9;
      margin: 0;
    }

    .subtitle {
      margin-top: 24px;
      font-size: 15px;
      color: #555;
    }

    section {
      margin-top: 72px;
    }

    h2 {
      font-size: 13px;
      font-weight: 400;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: #777;
      margin-bottom: 20px;
    }

    p, pre {
      font-size: 15px;
      line-height: 1.8;
    }

    pre {
      margin: 0;
      font-family: inherit;
      color: #333;
      white-space: pre-wrap;
    }

    .vertical {
      writing-mode: vertical-rl;
      text-orientation: upright;
      letter-spacing: 0.4em;
      font-size: 18px;
      color: #333;
      align-self: center;
      opacity: 0.65;
    }

    .line {
      width: 1px;
      height: 160px;
      background: #1f1f1f;
      opacity: 0.18;
      margin: 40px auto;
    }

    footer {
      margin-top: 96px;
      color: #777;
      font-size: 13px;
    }

    @media (max-width: 720px) {
      main {
        grid-template-columns: 1fr;
        padding: 40px 24px;
      }

      .vertical {
        writing-mode: horizontal-tb;
        letter-spacing: 0.2em;
        font-size: 14px;
        order: -1;
      }
    }
  </style>
</head>

<body>
  <main>
    <div class="content">
      <div class="mark">MINIMAL · LINUX · OPEN SOURCE</div>

      <h1>Rizza</h1>

      <div class="subtitle">
        DevOps Engineer · quiet infrastructure · reliable systems
      </div>

      <section>
        <h2>About</h2>
        <p>
          I build simple infrastructure with clean automation,
          minimal noise, and a linux-first mindset.
        </p>
      </section>

      <section>
        <h2>Stack</h2>
        <pre>Linux
Docker · Kubernetes
Terraform · Ansible
GitHub Actions · GitLab CI
Prometheus · Grafana
AWS · GCP</pre>
      </section>

      <section>
        <h2>Principles</h2>
        <pre>minimalism
open source
independence
stability over noise</pre>
      </section>

      <footer>
        reduce dependencies — increase freedom
      </footer>
    </div>

    <div class="vertical">
      余白
      <div class="line"></div>
      静けさ
      <div class="line"></div>
      自由
    </div>
  </main>
</body>
</html>
