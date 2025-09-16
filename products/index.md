---
layout: default
title: "Products - AuraPixel"
description: "Explore AuraPixel's suite of innovative SaaS tools, extensions, and apps designed to boost your productivity."
---

<section class="page-header">
  <div class="container">
    <h1>Our Products</h1>
    <p>Innovative tools designed to boost your productivity</p>
  </div>
</section>

<section class="products-showcase-section">
  <div class="container">
    <div class="products-grid">
      <div class="product-showcase-card">
        <div class="product-image">
          <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" style="margin: 2rem auto;"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line><polyline points="10 9 9 9 8 9"></polyline></svg>
        </div>
        <div class="product-content">
          <h2>Prompt Book</h2>
          <p class="product-tagline">Your AI Prompt Command Center</p>
          <p>A privacy-first browser extension designed to help you store, organize, and instantly inject your best prompts into any AI chatbot.</p>
          <div class="product-features">
            <span class="feature-tag">Browser Extension</span>
            <span class="feature-tag">AI Tools</span>
            <span class="feature-tag">Productivity</span>
          </div>
          <a href="{{ site.baseurl }}/products/prompt-book" class="btn btn-primary">Learn More</a>
        </div>
      </div>
      
      <div class="product-showcase-card coming-soon">
        <div class="product-image">
          <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" style="margin: 2rem auto;"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect><line x1="3" y1="9" x2="21" y2="9"></line><line x1="9" y1="21" x2="9" y2="9"></line></svg>
        </div>
        <div class="product-content">
          <div class="coming-soon-badge">Coming Soon</div>
          <h2>TaskFlow</h2>
          <p class="product-tagline">Streamlined Project Management</p>
          <p>An intuitive task tracking and workflow optimization tool designed to help teams collaborate efficiently and deliver projects on time.</p>
          <div class="product-features">
            <span class="feature-tag">Web App</span>
            <span class="feature-tag">Project Management</span>
            <span class="feature-tag">Collaboration</span>
          </div>
          <a href="#" class="btn btn-outline disabled">Stay Tuned</a>
        </div>
      </div>
      
      <div class="product-showcase-card coming-soon">
        <div class="product-image">
          <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" style="margin: 2rem auto;"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
        </div>
        <div class="product-content">
          <div class="coming-soon-badge">Coming Soon</div>
          <h2>PocketSync</h2>
          <p class="product-tagline">Seamless File Synchronization</p>
          <p>Keep your files and notes synchronized across all your devices with our secure cloud solution, designed for professionals on the go.</p>
          <div class="product-features">
            <span class="feature-tag">Mobile App</span>
            <span class="feature-tag">Cloud Storage</span>
            <span class="feature-tag">Synchronization</span>
          </div>
          <a href="#" class="btn btn-outline disabled">Stay Tuned</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="cta-section">
  <div class="container">
    <h2>Ready to Boost Your Productivity?</h2>
    <p>Explore our innovative tools designed to help you work smarter, not harder.</p>
    <a href="{{ site.baseurl }}/products/prompt-book" class="btn btn-lg">Try Prompt Book Today</a>
  </div>
</section>

<style>
  .page-header {
    padding: 6rem 0 3rem;
    text-align: center;
    background: var(--gradient-primary);
    color: white;
    margin-bottom: 4rem;
  }
  
  .page-header h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }
  
  .page-header p {
    font-size: 1.25rem;
    opacity: 0.9;
    max-width: 600px;
    margin: 0 auto;
  }
  
  .products-showcase-section {
    padding: 0 0 4rem;
  }
  
  .products-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 3rem;
  }
  
  .product-showcase-card {
    display: flex;
    flex-wrap: wrap;
    background-color: var(--color-card-bg);
    border-radius: 0.5rem;
    overflow: hidden;
    box-shadow: 0 4px 6px var(--color-card-shadow);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    position: relative;
  }
  
  .product-showcase-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 15px var(--color-card-shadow);
  }
  
  .product-showcase-card.coming-soon {
    opacity: 0.8;
  }
  
  .coming-soon-badge {
    position: absolute;
    top: 1rem;
    right: 1rem;
    background-color: var(--color-text-secondary);
    color: white;
    padding: 0.25rem 0.75rem;
    border-radius: 2rem;
    font-size: 0.75rem;
    font-weight: 600;
  }
  
  .product-image {
    flex: 0 0 300px;
    background-color: var(--color-bg-secondary);
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--color-primary);
  }
  
  .product-content {
    flex: 1;
    padding: 2rem;
    min-width: 300px;
  }
  
  .product-tagline {
    color: var(--color-primary);
    font-weight: 500;
    margin-bottom: 1rem;
  }
  
  .product-features {
    margin: 1.5rem 0;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  
  .feature-tag {
    background-color: var(--color-bg-secondary);
    color: var(--color-text-secondary);
    padding: 0.25rem 0.75rem;
    border-radius: 2rem;
    font-size: 0.75rem;
  }
  
  .btn.disabled {
    opacity: 0.6;
    cursor: not-allowed;
  }
  
  @media (min-width: 992px) {
    .product-showcase-card {
      flex-wrap: nowrap;
    }
  }
</style>
