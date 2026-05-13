---
icon: lucide/bone
title: Home
---

# Hello, it’s Gara!

[:fontawesome-brands-qq:&nbsp;&nbsp;QQ](https://qm.qq.com/q/fhDRf3qNBC){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-x-twitter:&nbsp;&nbsp;Twitter](https://x.com/perifural){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-discord:&nbsp;&nbsp;Discord](#){ #discord-copy .md-button style="width: 180px; text-align: center;" }
<span id="discord-copy-indicator" style="margin-left: 8px; opacity: 0;"></span>

[:fontawesome-brands-github:&nbsp;&nbsp;GitHub](https://github.com/perifural){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-linkedin:&nbsp;&nbsp;LinkedIn](https://github.com/perifural){ .md-button target="_blank" style="width: 180px; text-align: center;" }


<script>
document.getElementById("discord-copy")?.addEventListener("click", async (e) => {
  e.preventDefault();

  await navigator.clipboard.writeText("perifural");

  const indicator = document.getElementById("discord-copy-indicator");
  indicator.textContent = "✓ Copied!";
  indicator.style.opacity = "1";

  setTimeout(() => {
    indicator.style.opacity = "0";
  }, 1500);
});
</script>
