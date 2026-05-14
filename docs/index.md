---
icon: lucide/bone
title: Home
---

# Hello, it’s Gara!

<img class="avatar avatar--soft" src="images/avatar.jpg" alt="Caramel Gara">

[:fontawesome-brands-qq:&nbsp;&nbsp;QQ](https://qm.qq.com/q/fhDRf3qNBC){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-x-twitter:&nbsp;&nbsp;Twitter](https://x.com/perifural){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-discord:&nbsp;&nbsp;Discord](#){ #discord-copy .md-button style="width: 180px; text-align: center;" }
<span id="discord-copy-indicator" style="margin-left: 8px; opacity: 0;"></span>

[:fontawesome-brands-github:&nbsp;&nbsp;GitHub](https://github.com/perifural){ .md-button target="_blank" style="width: 180px; text-align: center;" }

[:fontawesome-brands-linkedin:&nbsp;&nbsp;LinkedIn](https://www.linkedin.com/in/zhe-w/){ .md-button target="_blank" style="width: 180px; text-align: center;" }


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

<style>
.avatar {
	width: 180px;
	height: 180px;
	object-fit: cover;
	background-position: center;
	margin-bottom: var(--spacing-l);
  }

   /* Modifier for no avatar rounding */
   .avatar--none {
	border-radius: 0%;
  }

  /* Modifier for rounded avatar */
  .avatar--rounded {
	border-radius: 50%;
  }

  /* Modifier for slightly rounded corners */
  .avatar--soft {
	border-radius: 16px;
  }
  </style>