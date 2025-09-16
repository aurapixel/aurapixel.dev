---
layout: default
title: "Prompt Book - AI Prompt Management Assistant"
description: "Store, organize, and instantly inject your best prompts into any AI chatbot with our privacy-first browser extension."
---

<section class="product-hero-section">
  <div class="container">
    <div class="product-hero-content">
      <h1>Prompt Book</h1>
      <p class="product-tagline">Your AI Prompt Command Center</p>
      <p class="product-description">A privacy-first browser extension designed to help you store, organize, and instantly inject your best prompts into any AI chatbot. Built for speed, consistency, and control across platforms like ChatGPT, Claude, Gemini, Copilot, and more.</p>
      <div class="product-cta">
        <a href="#pricing" class="btn btn-primary btn-lg">View Pricing</a>
        <a href="#features" class="btn btn-outline btn-lg">Explore Features</a>
      </div>
    </div>
    <div class="product-hero-image">
      <img src="{{ site.baseurl }}/assets/images/prompt-book-hero.svg" alt="Prompt Book Interface" class="product-image">
    </div>
  </div>
</section>

<section id="features" class="product-features-section">
  <div class="container">
    <div class="section-header">
      <h2>Why Prompt Book?</h2>
      <p>The ultimate tool for AI prompt management and productivity</p>
    </div>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>
        </div>
        <h3>Save Time</h3>
        <p>Stop rewriting prompts and reuse your proven ones with a single click.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line><polyline points="10 9 9 9 8 9"></polyline></svg>
        </div>
        <h3>Stay Organized</h3>
        <p>Keep your best prompts at your fingertips—organized, searchable, and ready to inject in one click.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="9 11 12 14 22 4"></polyline><path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11"></path></svg>
        </div>
        <h3>Ensure Consistency</h3>
        <p>Maintain consistent output quality across different tools and sessions.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="7 10 12 15 17 10"></polyline><line x1="12" y1="15" x2="12" y2="3"></line></svg>
        </div>
        <h3>Data Control</h3>
        <p>Back up and restore your prompt library with confidence.</p>
      </div>
    </div>
  </div>
</section>

<section class="product-details-section">
  <div class="container">
    <div class="product-details-content">
      <div class="product-details-text">
        <h2>Key Features</h2>
        <ul class="feature-list">
          <li>
            <strong>Prompt Library:</strong> Add, edit, and delete prompts with titles and full content. Organize with folders, tags, and colors. Tracks usage per prompt.
          </li>
          <li>
            <strong>Lightning-Fast Retrieval:</strong> Smart search across titles and content. One-click injection into chat inputs. A floating icon overlay appears on supported sites.
          </li>
          <li>
            <strong>Sorting & Filtering:</strong> Sort by Alphabetical, Date, or Frequency (Asc/Desc). Includes quick filters and folder filtering with custom folder ordering.
          </li>
          <li>
            <strong>Data Portability:</strong> Import/Export backups in JSON (full-fidelity with metadata) and CSV.
          </li>
          <li>
            <strong>Cloud & Backup:</strong> Features Google Drive backup/restore, sync status, and a daily scheduled sync.
          </li>
          <li>
            <strong>UI & Experience:</strong> A clean, responsive Svelte-powered UI with vertical tabs for Account, Data, About, and Help. Provides toasts and progress feedback.
          </li>
          <li>
            <strong>Privacy & Security:</strong> Local-first storage with granular permissions. OAuth scopes are limited to profile and Drive where used, with transparent host permissions.
          </li>
        </ul>
      </div>
      <div class="product-details-image">
        <img src="{{ site.baseurl }}/assets/images/prompt-book-features.svg" alt="Prompt Book Features" class="product-image">
      </div>
    </div>
  </div>
</section>

<section class="product-how-it-works-section">
  <div class="container">
    <div class="section-header">
      <h2>How It Works</h2>
      <p>Simple, intuitive, and powerful prompt management</p>
    </div>
    <div class="how-it-works-steps">
      <div class="step-card">
        <div class="step-number">1</div>
        <h3>Store & Organize</h3>
        <p>Save prompts with titles and folder association. The tool uses persistent folder IDs and custom ordering via preferences.</p>
      </div>
      <div class="step-card">
        <div class="step-number">2</div>
        <h3>Find & Use</h3>
        <p>Type to filter; a fast derived search combines search, folder, and sort. Click "Use" to inject the prompt into chat inputs.</p>
      </div>
      <div class="step-card">
        <div class="step-number">3</div>
        <h3>Back Up & Restore</h3>
        <p>Export or import your library. The Google Drive integration tracks the last sync time.</p>
      </div>
      <div class="step-card">
        <div class="step-number">4</div>
        <h3>Stay in Sync (Premium)</h3>
        <p>Uses Firestore for profile and settings sync. It auto-creates a profile on first login and performs a daily scheduled sync at 14:00.</p>
      </div>
    </div>
  </div>
</section>

<section class="product-compatibility-section">
  <div class="container">
    <div class="section-header">
      <h2>Supported Websites</h2>
      <p>Works seamlessly with your favorite AI platforms</p>
    </div>
    <div class="compatibility-grid">
      <div class="compatibility-item">
        <h3>ChatGPT</h3>
        <p>chat.openai.com, chatgpt.com</p>
      </div>
      <div class="compatibility-item">
        <h3>Claude</h3>
        <p>claude.ai</p>
      </div>
      <div class="compatibility-item">
        <h3>Google Gemini/Bard</h3>
        <p>gemini.google.com, bard.google.com</p>
      </div>
      <div class="compatibility-item">
        <h3>Microsoft Copilot</h3>
        <p>copilot.microsoft.com</p>
      </div>
      <div class="compatibility-item">
        <h3>And More</h3>
        <p>You.com, Poe, Character.AI, Hugging Face, Perplexity</p>
      </div>
      <div class="compatibility-item">
        <h3>Universal Support</h3>
        <p>Works on most sites with a standard text input</p>
      </div>
    </div>
  </div>
</section>

<section class="product-audience-section">
  <div class="container">
    <div class="section-header">
      <h2>Who It's For</h2>
      <p>Designed for everyone who works with AI tools</p>
    </div>
    <div class="audience-grid">
      <div class="audience-card">
        <div class="audience-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20h9"></path><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"></path></svg>
        </div>
        <h3>Creators & Researchers</h3>
        <p>Ideal for curating prompts for content generation, brainstorming, and analysis.</p>
      </div>
      <div class="audience-card">
        <div class="audience-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"></polyline><polyline points="8 6 2 12 8 18"></polyline></svg>
        </div>
        <h3>Developers & Analysts</h3>
        <p>Helps standardize prompts for tasks like code review, refactoring, and data analysis.</p>
      </div>
      <div class="audience-card">
        <div class="audience-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
        </div>
        <h3>Teams & Consultants</h3>
        <p>Facilitates consistent prompt patterns across clients and projects with shareable backups.</p>
      </div>
    </div>
  </div>
</section>

<section id="pricing" class="product-pricing-section">
  <div class="container">
    <div class="section-header">
      <h2>Plans & Pricing</h2>
      <p>Choose the plan that fits your workflow</p>
    </div>
    <div class="pricing-grid">
      <div class="pricing-card">
        <div class="pricing-header">
          <h3>Free</h3>
          <div class="price">$0<span>/forever</span></div>
        </div>
        <div class="pricing-features">
          <ul>
            <li>Prompt library: add/edit/delete</li>
            <li>Search and quick input</li>
            <li>Basic folders and tags</li>
            <li>Core UI and quick filters</li>
            <li>Local storage</li>
            <li>In-session sorting (alphabetical/date/frequency)</li>
          </ul>
        </div>
        <div class="pricing-cta">
          <a href="#" class="btn btn-outline">Get Started</a>
        </div>
      </div>
      <div class="pricing-card featured">
        <div class="pricing-badge">Most Popular</div>
        <div class="pricing-header">
          <h3>Premium Monthly</h3>
          <div class="price">$4.99<span>/month</span></div>
        </div>
        <div class="pricing-features">
          <ul>
            <li><strong>Everything in Free</strong></li>
            <li>Usage count enabled</li>
            <li>Custom folder ordering persistence</li>
            <li>Data export (JSON/CSV)</li>
            <li>Google Drive backup + restore</li>
            <li>Cloud settings sync (login, daily scheduled sync)</li>
            <li>Priority updates and support</li>
          </ul>
        </div>
        <div class="pricing-cta">
          <a href="#" class="btn btn-primary">Subscribe Now</a>
        </div>
      </div>
      <div class="pricing-card">
        <div class="pricing-header">
          <h3>Premium Lifetime</h3>
          <div class="price">$39<span>/one-time</span></div>
        </div>
        <div class="pricing-features">
          <ul>
            <li><strong>All Premium Monthly features</strong></li>
            <li>One-time payment</li>
          </ul>
        </div>
        <div class="pricing-cta">
          <a href="#" class="btn btn-outline">Buy Now</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="product-roadmap-section">
  <div class="container">
    <div class="section-header">
      <h2>Roadmap Highlights</h2>
      <p>What's coming next for Prompt Book</p>
    </div>
    <div class="roadmap-items">
      <div class="roadmap-item">
        <div class="roadmap-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
        </div>
        <h3>Team sharing and collaboration options</h3>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line><polyline points="10 9 9 9 8 9"></polyline></svg>
        </div>
        <h3>Advanced templates with variables and dynamic fields</h3>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"></polyline><polyline points="8 6 2 12 8 18"></polyline></svg>
        </div>
        <h3>More integrations and site-specific enhancements</h3>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="17 8 12 3 7 8"></polyline><line x1="12" y1="3" x2="12" y2="15"></line></svg>
        </div>
        <h3>Automated periodic Google Drive backups</h3>
      </div>
    </div>
  </div>
</section>

<section class="cta-section">
  <div class="container">
    <h2>Ready to Boost Your AI Productivity?</h2>
    <p>Install the extension today and start organizing your AI prompts like a pro.</p>
    <a href="#" class="btn btn-lg">Get Prompt Book Now</a>
  </div>
</section>

<style>
  /* Product page specific styles */
  .product-hero-section {
    padding: 6rem 0;
    position: relative;
    overflow: hidden;
  }
  
  .product-hero-content {
    max-width: 600px;
  }
  
  .product-tagline {
    font-size: 1.5rem;
    color: var(--color-primary);
    margin-bottom: 1rem;
    font-weight: 500;
  }
  
  .product-description {
    font-size: 1.125rem;
    margin-bottom: 2rem;
    color: var(--color-text-secondary);
  }
  
  .product-cta {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-bottom: 2rem;
  }
  
  .product-hero-image {
    margin-top: 3rem;
    text-align: center;
  }
  
  .product-image {
    max-width: 100%;
    border-radius: 0.5rem;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
  }
  
  .product-features-section {
    padding: 4rem 0;
    background-color: var(--color-bg-secondary);
  }
  
  .product-details-section {
    padding: 4rem 0;
  }
  
  .product-details-content {
    display: flex;
    flex-wrap: wrap;
    gap: 3rem;
    align-items: center;
  }
  
  .product-details-text {
    flex: 1;
    min-width: 300px;
  }
  
  .product-details-image {
    flex: 1;
    min-width: 300px;
    text-align: center;
  }
  
  .feature-list {
    list-style-type: none;
    padding: 0;
  }
  
  .feature-list li {
    margin-bottom: 1rem;
    padding-left: 1.5rem;
    position: relative;
  }
  
  .feature-list li::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0.5rem;
    width: 0.5rem;
    height: 0.5rem;
    border-radius: 50%;
    background-color: var(--color-primary);
  }
  
  .product-how-it-works-section {
    padding: 4rem 0;
    background-color: var(--color-bg-secondary);
  }
  
  .how-it-works-steps {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .step-card {
    background-color: var(--color-card-bg);
    border-radius: 0.5rem;
    padding: 2rem;
    box-shadow: 0 4px 6px var(--color-card-shadow);
    position: relative;
  }
  
  .step-number {
    position: absolute;
    top: -1rem;
    left: -1rem;
    width: 2.5rem;
    height: 2.5rem;
    border-radius: 50%;
    background: var(--gradient-primary);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 1.25rem;
  }
  
  .product-compatibility-section {
    padding: 4rem 0;
  }
  
  .compatibility-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .compatibility-item {
    text-align: center;
    padding: 1.5rem;
    background-color: var(--color-bg-secondary);
    border-radius: 0.5rem;
  }
  
  .compatibility-item h3 {
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  
  .compatibility-item p {
    color: var(--color-text-secondary);
    font-size: 0.875rem;
    margin: 0;
  }
  
  .product-audience-section {
    padding: 4rem 0;
    background-color: var(--color-bg-secondary);
  }
  
  .audience-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .audience-card {
    background-color: var(--color-card-bg);
    border-radius: 0.5rem;
    padding: 2rem;
    box-shadow: 0 4px 6px var(--color-card-shadow);
  }
  
  .audience-icon {
    width: 3rem;
    height: 3rem;
    border-radius: 50%;
    background: var(--gradient-primary);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 1.5rem;
  }
  
  .product-pricing-section {
    padding: 4rem 0;
  }
  
  .pricing-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .pricing-card {
    background-color: var(--color-card-bg);
    border-radius: 0.5rem;
    padding: 2rem;
    box-shadow: 0 4px 6px var(--color-card-shadow);
    position: relative;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: flex;
    flex-direction: column;
  }
  
  .pricing-card.featured {
    transform: scale(1.05);
    box-shadow: 0 10px 20px var(--color-card-shadow);
    border: 2px solid var(--color-primary);
    z-index: 1;
  }
  
  .pricing-badge {
    position: absolute;
    top: -1rem;
    right: 1rem;
    background: var(--gradient-primary);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 2rem;
    font-size: 0.875rem;
    font-weight: 600;
  }
  
  .pricing-header {
    text-align: center;
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid var(--color-border);
  }
  
  .pricing-header h3 {
    margin-bottom: 1rem;
  }
  
  .price {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--color-primary);
  }
  
  .price span {
    font-size: 1rem;
    font-weight: 400;
    color: var(--color-text-secondary);
  }
  
  .pricing-features {
    flex-grow: 1;
    margin-bottom: 2rem;
  }
  
  .pricing-features ul {
    list-style-type: none;
    padding: 0;
  }
  
  .pricing-features li {
    margin-bottom: 0.75rem;
    padding-left: 1.5rem;
    position: relative;
  }
  
  .pricing-features li::before {
    content: "✓";
    position: absolute;
    left: 0;
    color: var(--color-primary);
    font-weight: 700;
  }
  
  .pricing-cta {
    text-align: center;
  }
  
  .product-roadmap-section {
    padding: 4rem 0;
    background-color: var(--color-bg-secondary);
  }
  
  .roadmap-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .roadmap-item {
    background-color: var(--color-card-bg);
    border-radius: 0.5rem;
    padding: 2rem;
    box-shadow: 0 4px 6px var(--color-card-shadow);
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .roadmap-icon {
    width: 3rem;
    height: 3rem;
    border-radius: 50%;
    background: var(--gradient-primary);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 1.5rem;
  }
  
  @media (max-width: 767px) {
    .pricing-card.featured {
      transform: scale(1);
    }
  }
</style>
