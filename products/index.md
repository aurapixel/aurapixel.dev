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
        <div class="product-image" style="text-align: center; padding: 2rem 0;">
          <img src="{{ site.baseurl }}/assets/images/magic-book-1024-transparent.png" alt="Prompt Book" style="width: 200px; height: 200px; object-fit: contain;">
        </div>
        <div class="product-content">
          <h2>Prompt Book</h2>
          <p class="product-tagline">Your magical companion for managing AI prompts</p>
          <p>A privacy-first browser extension designed to help you store, organize, and instantly inject your best prompts into any AI chatbot.</p>
          <div class="product-features">
            <span class="feature-tag">Browser Extension</span>
            <span class="feature-tag">AI Tools</span>
            <span class="feature-tag">Productivity</span>
          </div>
          <a href="{{ site.baseurl }}/products/prompt-book" class="btn btn-primary">Learn More</a>
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
