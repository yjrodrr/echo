<script>
  let code = '';

  const CORRECT_HASH = '3865e98e8d3fe3316c6b8cb24219bf0847bdd11b9f9b1940dda302111134c297';
  const encoded = 'amZkaWplLmh0bWw=';

  async function computeSHA256(input) {
    const msgBuffer = new TextEncoder().encode(input);
    const hashBuffer = await crypto.subtle.digest('SHA-256', msgBuffer);
    const hashArray = Array.from(new Uint8Array(hashBuffer));
    return hashArray.map(b => b.toString(16).padStart(2, '0')).join('');
  }

  async function check() {
    const trimmed = code.trim();
    if (!trimmed) return;

    const hash = await computeSHA256(trimmed);
    if (hash === CORRECT_HASH) {
      window.location.href = atob(encoded);
    }
  }

  function handleKeydown(e) {
    if (e.key === 'Enter') check();
  }
</script>

<svelte:head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
</svelte:head>

<div class="root">
  <input
    type="text"
    bind:value={code}
    placeholder="ㅤ"
    autocomplete="off"
    on:keydown={handleKeydown}
  />
  <button on:click={check}>?</button>
</div>

<style>
  :global(:root),
  :global(html),
  :global(body) {
    margin: 0 !important;
    padding: 0 !important;
    border: 0 !important;
    width: 100% !important;
    height: 100% !important;
    min-height: -webkit-fill-available !important;
    background: #000000 !important;
    color: #eeeeee;
    font-family: system-ui, sans-serif;
    overflow: hidden !important;
    overscroll-behavior: none;
    touch-action: manipulation;
  }

  .root {
    position: fixed;
    inset: 0;
    width: 100vw;
    height: 100vh;
    margin: 0;
    padding: 0;
    background: #000000;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 28px;
  }

  input {
    padding: 14px 24px;
    font-size: 22px;
    width: 260px;
    text-align: center;
    background: #0f0f0f;
    color: #e0e0e0;
    border: 1px solid #333;
    border-radius: 8px;
    outline: none;
  }

  input:focus {
    border-color: #555;
  }

  button {
    padding: 14px 52px;
    font-size: 20px;
    background: #1a1a1a;
    color: #e0e0e0;
    border: 1px solid #444;
    border-radius: 8px;
    cursor: pointer;
  }

  button:hover {
    background: #2a2a2a;
  }

  button:active {
    background: #3a3a3a;
  }

  /* Usuwanie pasków przewijania i ramek przeglądarki */
  :global(body::-webkit-scrollbar),
  :global(*)::-webkit-scrollbar {
    display: none;
  }
</style>
