<template>
  <footer class="site-footer">
    <div class="footer-inner">
      <div class="footer-top">
        <!-- Left: Brand -->
        <div class="footer-brand-section">
          <div class="footer-brand">
            <img src="/logo.jpg" alt="YourwayAI Logo" class="footer-logo" />
            <span class="footer-name">YourwayAI</span>
          </div>
          <p class="footer-tagline">发现优质的免费开源软件，打破信息差，拥抱开源精神。</p>
        </div>

        <!-- Right: Links -->
        <div class="footer-links-section">
          <div class="footer-links">
            <a href="/sponsor/ywc-resume" class="footer-link sponsor-link">🏅 赞助我们</a>
            <span class="footer-link-divider">|</span>
            <a href="https://github.com" target="_blank" rel="noopener" class="footer-link">GitHub</a>
            <a href="https://x.com" target="_blank" rel="noopener" class="footer-link">X</a>
            <a href="https://threads.net" target="_blank" rel="noopener" class="footer-link">Threads</a>
            <a href="https://openai.com" target="_blank" rel="noopener" class="footer-link">OpenAI</a>
            <a href="https://gemini.google.com" target="_blank" rel="noopener" class="footer-link">Gemini</a>
            <a href="https://claude.ai" target="_blank" rel="noopener" class="footer-link">Claude</a>
          </div>
        </div>
      </div>

      <!-- Divider -->
      <div class="footer-divider"></div>

      <!-- Bottom Row -->
      <div class="footer-bottom">
        <span class="footer-copyright">© 2026-present YourwayAI. All rights reserved.</span>
        <a href="mailto:brucemi@yourwaycareer.com" class="footer-contact">
          <span class="contact-icon">✉️</span>
          brucemi@yourwaycareer.com
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.site-footer {
  margin-top: 3rem;
  border-top: 1px solid var(--vp-c-divider);
  background: var(--vp-c-bg-soft);
  padding: 2.5rem 1.5rem 2rem;
}

.footer-inner {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.footer-top {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 2rem;
}

/* Brand Section */
.footer-brand-section {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
  max-width: 400px;
}

.footer-brand {
  display: flex;
  align-items: center;
  gap: 0.6rem;
}

.footer-logo {
  width: 32px;
  height: 32px;
  border-radius: 8px;
  object-fit: cover;
}

.footer-name {
  font-size: 1.2rem;
  font-weight: 700;
  color: var(--vp-c-text-1);
  letter-spacing: -0.01em;
}

.footer-tagline {
  font-size: 0.9rem;
  color: var(--vp-c-text-2);
  margin: 0;
  line-height: 1.6;
}

/* Links Section */
.footer-links-section {
  display: flex;
  flex-direction: column;
}

.footer-links {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 1.2rem;
}

.footer-link {
  font-size: 0.9rem;
  color: var(--vp-c-text-2);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}

.footer-link:hover {
  color: var(--vp-c-brand-1);
}

.sponsor-link {
  color: var(--vp-c-brand-1);
  font-weight: 600;
}

.footer-link-divider {
  color: var(--vp-c-divider);
  font-size: 0.8rem;
}

/* Divider */
.footer-divider {
  width: 100%;
  height: 1px;
  background: var(--vp-c-divider);
  margin: 0.5rem 0;
}

/* Bottom row */
.footer-bottom {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 1.2rem;
}

.footer-copyright {
  font-size: 0.85rem;
  color: var(--vp-c-text-3);
}

.footer-contact {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  font-size: 0.85rem;
  color: var(--vp-c-brand-1);
  text-decoration: none;
  font-weight: 600;
  transition: opacity 0.2s;
}

.footer-contact:hover {
  opacity: 0.75;
}

.contact-icon {
  font-size: 0.9rem;
}

/* Responsive */
@media (max-width: 768px) {
  .footer-top {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .footer-brand-section {
    align-items: center;
  }
  
  .footer-links {
    justify-content: center;
  }
  
  .footer-bottom {
    justify-content: center;
    text-align: center;
  }
}
</style>
