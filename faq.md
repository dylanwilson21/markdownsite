---
layout: default
title: FAQ
description: "Frequently asked questions about Galoy bitcoin banking software, core banking systems, and bitcoin-backed lending platforms. Learn about our products, security, compliance, and how to deploy bitcoin banking infrastructure."
keywords: "galoy faq, bitcoin banking questions, core banking system faq, bitcoin loan platform questions, fintech software help, banking software support, bitcoin infrastructure faq, galoy help, banking software questions"
---

# Frequently Asked Questions

## General Questions

### What is Galoy?
Galoy provides banking software solutions designed to empower innovative organizations in leveraging the full potential of Bitcoin and other digital assets.

### Who can use Galoy?
Galoy is designed for:
- Banks and financial institutions seeking Bitcoin integration
- Enterprises building digital asset products
- Organizations offering Bitcoin-backed lending services
- Businesses needing robust Bitcoin payment infrastructure

## Technical Questions

### What products does Galoy offer?
- **Lana**: Bitcoin loans platform for digital asset-backed lending
- **Bria**: Bitcoin payments hub with Lightning Network integration
- **Cala**: Bitcoin-native double-entry accounting ledger
- **Stablesats**: Hedging engine for Bitcoin-native stable balances
- **Blink Wallet**: Popular Lightning-native mobile Bitcoin wallet

### Do I need to be a Bitcoin expert to use Galoy?
No. Galoy is designed to handle the technical complexity of Bitcoin operations while providing simple interfaces for end users.

### Can I integrate Galoy with existing systems?
Yes. Galoy's modular architecture allows seamless integration with existing banking infrastructure, enterprise financial systems, and custom applications.

## Deployment Questions

### How difficult is it to deploy Galoy?
Galoy provides multiple deployment options:
- **Docker Compose** - For development and testing
- **Kubernetes** - For production deployments
- **Cloud providers** - Pre-configured for AWS, GCP, and others
- **Managed hosting** - We can host and manage it for you

### What are the system requirements?
Minimum requirements vary by deployment size:
- **Small deployment**: 4 CPU cores, 8GB RAM, 100GB storage
- **Medium deployment**: 8 CPU cores, 16GB RAM, 500GB storage
- **Large deployment**: 16+ CPU cores, 32GB+ RAM, 1TB+ storage

## Business Questions

### How much does Galoy cost?
Galoy Core is completely free and open source. Costs may include infrastructure hosting, professional services, and managed hosting.

### What kind of support is available?
We offer:
- **Community support** - Through GitHub and community channels
- **Documentation** - Comprehensive guides and tutorials
- **Professional services** - Paid consulting and development
- **Managed hosting** - Full-service hosting with support

### Can Galoy handle regulatory compliance?
Galoy provides tools that help with compliance, including transaction monitoring, user verification workflows, and audit trails. However, compliance requirements vary by jurisdiction.

## Security Questions

### How secure is Galoy?
Security is a top priority. Galoy includes multi-signature wallet support, encrypted data storage, secure API authentication, and regular security audits.

### Can I audit the security myself?
Yes. Being open source means you can review all the code and run your own security assessments.

## Getting Help

### Where can I get more information?
- **GitHub and Documentation**: [github.com/GaloyMoney](https://github.com/GaloyMoney)
- **Contact**: [biz@galoy.io](mailto:biz@galoy.io)
  
### Join our developer community for discussions, support, and collaboration.

<div class="contact-dropdown">
  <button class="contact-dropdown-btn" onclick="toggleCommunityDropdown()">Join Community ▼</button>
  <div class="contact-dropdown-content" id="communityDropdown">
    <div class="contact-item">
      <strong>Public Telegram</strong>
      <input type="text" value="https://t.me/galoyofficial" readonly onclick="copyToClipboard(this)">
    </div>
    <div class="contact-item">
      <strong>Public Discord</strong>
      <input type="text" value="https://discord.gg/MzWus8Nvzw" readonly onclick="copyToClipboard(this)">
    </div>
  </div>
</div>

<script>
function toggleCommunityDropdown() {
  document.getElementById("communityDropdown").classList.toggle("show");
}

function copyToClipboard(element) {
  element.select();
  document.execCommand('copy');

  // Show feedback
  const originalValue = element.value;
  element.value = "Copied!";
  setTimeout(() => {
    element.value = originalValue;
  }, 1000);
}

// Close dropdown when clicking outside
window.onclick = function(event) {
  if (!event.target.matches('.contact-dropdown-btn')) {
    var dropdowns = document.getElementsByClassName("contact-dropdown-content");
    for (var i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>

<style>
.contact-dropdown {
  position: relative;
  display: inline-block;
  margin: 1rem 0;
}

.contact-dropdown-btn {
  background-color: #f7931a;
  color: white;
  padding: 0.75rem 1.5rem;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-family: "Source Code Pro", monospace;
  font-weight: 500;
}

.contact-dropdown-btn:hover {
  background-color: #e6830f;
}

.contact-dropdown-content {
  display: none;
  position: absolute;
  background-color: #161b22;
  min-width: 300px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  border: 1px solid #30363d;
  border-radius: 6px;
  padding: 1rem;
  top: 100%;
  left: 0;
}

.contact-dropdown-content.show {
  display: block;
}

.contact-item {
  margin-bottom: 1rem;
}

.contact-item:last-child {
  margin-bottom: 0;
}

.contact-item strong {
  display: block;
  color: #f0f6fc;
  margin-bottom: 0.5rem;
  font-size: 14px;
}

.contact-item input {
  width: 100%;
  padding: 0.5rem;
  background-color: #21262d;
  border: 1px solid #30363d;
  border-radius: 4px;
  color: #f0f6fc;
  font-family: "Source Code Pro", monospace;
  font-size: 12px;
  cursor: pointer;
}

.contact-item input:focus {
  outline: none;
  border-color: #f7931a;
}

.contact-item input:hover {
  border-color: #484f58;
}
</style>

### How can I contribute to Galoy?
We welcome contributions through code, documentation, testing, and community support.

Still have questions? Feel free to reach out to us directly.