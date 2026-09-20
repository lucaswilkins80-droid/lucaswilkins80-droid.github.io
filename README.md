<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>FixUp.com | Host Discord Bots Like a Pro</title>
    <meta
      name="description"
      content="Deploy and manage Discord bots with file uploads, console access, live logs, and elite infrastructure."
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap"
      rel="stylesheet"
    />
    <style>
      :root {
        --bg: #06131f;
        --bg-2: #0d1d2f;
        --surface: rgba(12, 23, 36, 0.7);
        --surface-strong: rgba(15, 27, 42, 0.9);
        --card: rgba(12, 20, 32, 0.86);
        --line: rgba(255, 255, 255, 0.08);
        --text: #edf4ff;
        --muted: #b7c7dc;
        --primary: #7c5cff;
        --primary-2: #42d4ff;
        --success: #2ce4a1;
        --warning: #ffc857;
        --shadow: 0 24px 80px rgba(2, 10, 18, 0.7);
        --page-bg: linear-gradient(180deg, #040c14 0%, #071926 100%);
      }

      body[data-theme="light"] {
        --bg: #edf3ff;
        --bg-2: #dfeafc;
        --surface: rgba(255, 255, 255, 0.82);
        --surface-strong: rgba(255, 255, 255, 0.96);
        --card: rgba(255, 255, 255, 0.9);
        --line: rgba(27, 39, 56, 0.08);
        --text: #132033;
        --muted: #52647f;
        --primary: #5b4df6;
        --primary-2: #20b8ff;
        --success: #179c64;
        --warning: #d78a00;
        --shadow: 0 24px 80px rgba(25, 48, 84, 0.16);
        --page-bg: linear-gradient(180deg, #eff5ff 0%, #e9f1ff 100%);
      }

      * { box-sizing: border-box; }
      html { scroll-behavior: smooth; }
      body {
        margin: 0;
        font-family: "Inter", sans-serif;
        background:
          radial-gradient(circle at top left, rgba(124, 92, 255, 0.25), transparent 25%),
          radial-gradient(circle at top right, rgba(66, 212, 255, 0.2), transparent 30%),
          var(--page-bg);
        color: var(--text);
        transition: background 0.25s ease, color 0.25s ease;
      }
      img { max-width: 100%; display: block; }
      button, input { font: inherit; }
      button { cursor: pointer; }
      a { color: inherit; }

      .container { width: min(1180px, calc(100% - 32px)); margin: 0 auto; }
      .page-shell { position: relative; min-height: 100vh; overflow: hidden; }
      .page-shell::before {
        content: "";
        position: absolute;
        inset: 0;
        background-image: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80');
        background-size: cover;
        background-position: center;
        opacity: 0.12;
        filter: blur(2px);
        pointer-events: none;
      }
      header, main, footer { position: relative; z-index: 1; }

      .topbar {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 16px;
        padding: 22px 0 18px;
      }

      .brand {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        font-weight: 800;
        letter-spacing: -0.05em;
      }

      .brand-icon {... (2 KB left)
