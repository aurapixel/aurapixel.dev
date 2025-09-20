---
layout: default
title: "Prompt Book Privacy Policy"
description: "Privacy policy for the Prompt Book browser extension."
---

<main>
    <div class="privacy-header">
        <h1>Privacy Policy</h1>
        <h2 class="product-subtitle">Prompt Book</h2>
        <p class="subtitle">Last updated: September 16, 2025</p>
    </div>
    
    <div class="privacy-container">
        <div class="privacy-section">
            <h2>Overview</h2>
            <p>Prompt Book is a prompt assistant and management tool designed with a privacy-first approach. This policy explains how we handle your information when you use our extension.</p>
        </div>
        
        <div class="privacy-section">
            <h2>What We Collect</h2>
            <ul>
                <li>We do not collect personal information.</li>
                <li>We do not transmit your data to our servers or any third parties.</li>
                <li>We do not use analytics or tracking beacons.</li>
            </ul>
        </div>
        
        <div class="privacy-section">
            <h2>What We Store</h2>
            <ul>
                <li>The extension stores your prompts, folders/tags, and preferences in <code>chrome.storage</code> (local or sync, depending on your browser settings).</li>
                <li>This data stays in your browser profile (and may sync across your signed-in devices if you enable browser sync).</li>
                <li>You can export/import your data and delete it at any time via the extension UI or your browser's extension data controls.</li>
            </ul>
        </div>
        
        <div class="privacy-section">
            <h2>Access to Page Content</h2>
            <ul>
                <li>The extension only interacts with the current page when you explicitly invoke it (e.g., by clicking the toolbar icon, using a context menu, or on sites you allow).</li>
                <li>Content scripts are injected on demand to perform limited, non-destructive actions such as inserting text or showing a small UI/notification.</li>
                <li>The page content we access is used solely to fulfill your requested action. It is not stored outside of your browser storage and is never transmitted.</li>
            </ul>
        </div>
        
        <div class="privacy-section">
            <h2>Permissions and Why They're Needed</h2>
            
            <h3>storage</h3>
            <p>To save your prompts, folders/tags, and settings so they persist across sessions. No personal data is uploaded.</p>
            
            <h3>contextMenus</h3>
            <p>To provide optional right-click actions that you can explicitly invoke.</p>
            
            <h3>activeTab</h3>
            <p>To grant temporary access to the current tab only when you trigger the extension, enabling one-time page enhancements.</p>
            
            <h3>scripting</h3>
            <p>To inject/execute minimal content scripts on demand to perform requested actions (e.g., insert text, show a toast/popup).</p>
            
            <h3>host permissions</h3>
            <p>To allow content scripts to run on the sites you visit (or specific sites you choose) strictly to provide the features you request. No background scraping or cross-site tracking.</p>
        </div>
        
        <div class="privacy-section">
            <h2>Data Sharing and Sale</h2>
            <p>We do not sell, rent, or share your data with third parties.</p>
        </div>
        
        <div class="privacy-section">
            <h2>Security</h2>
            <p>We take reasonable measures to protect your data stored in <code>chrome.storage</code>, but no method of electronic storage is 100% secure.</p>
        </div>
        
        <div class="privacy-section">
            <h2>Changes to This Policy</h2>
            <p>We may update this policy from time to time. Material changes will be reflected in the extension's release notes and/or store listing with an updated effective date.</p>
        </div>
        
        <div class="last-updated">
            <p>Last updated: September 16, 2025</p>
        </div>
    </div>
</main>

<style>
    .privacy-header {
        text-align: center;
        margin-bottom: 2rem;
        padding: 2rem 0;
        background: var(--gradient-primary);
        color: white;
    }
    
    .privacy-header h1 {
        margin-bottom: 0.5rem;
    }
    
    .product-subtitle {
        font-size: 1.25rem;
        font-weight: 400;
        margin-bottom: 0.5rem;
        color: rgba(255, 255, 255, 0.9);
    }
    
    .subtitle {
        opacity: 0.8;
    }
    
    .privacy-container {
        max-width: 800px;
        margin: 0 auto;
        padding: 2rem;
    }
    
    .privacy-section {
        margin-bottom: 2rem;
    }
    
    .privacy-section h2 {
        color: var(--color-primary);
        margin-bottom: 1rem;
        padding-bottom: 0.5rem;
        border-bottom: 1px solid var(--color-border);
    }
    
    .privacy-section h3 {
        color: var(--color-text);
        margin: 1.5rem 0 0.5rem;
    }
    
    .privacy-section ul {
        padding-left: 1.5rem;
    }
    
    .privacy-section li {
        margin-bottom: 0.5rem;
    }
    
    code {
        background: var(--color-bg-secondary);
        padding: 0.2rem 0.4rem;
        border-radius: 0.25rem;
        font-family: monospace;
    }
    
    .last-updated {
        margin-top: 3rem;
        padding-top: 1rem;
        border-top: 1px solid var(--color-border);
        font-style: italic;
        opacity: 0.7;
    }
</style>
