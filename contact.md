---
layout: default
title: Contact
description: "Contact Galoy for bitcoin banking software demos, core banking consultations, and bitcoin-backed lending platform integration. Get started with enterprise-grade bitcoin banking infrastructure today."
keywords: "galoy contact, bitcoin banking demo, core banking consultation, bitcoin loan platform demo, fintech software contact, banking software sales, bitcoin infrastructure contact, galoy demo, banking software consultation"
---

# Get in Touch

Ready to transform your banking infrastructure? We're here to help you get started with Galoy's simple, secure, and scalable banking solutions.

## How Can We Help?

### Request a Demo
See Galoy's Core Banking Suite or Lana lending platform in action. Our team will walk you through the features and answer your questions.

[Request Demo](https://calendly.com/andrew-galoy/){: .btn}

### Schedule a Consultation
Need a custom solution or have specific requirements? Let's discuss how Galoy can be tailored to your institution's needs.

[Schedule Consultation](https://calendly.com/andrew-galoy/){: .btn}

### Contact Methods

<div class="contact-dropdown">
  <button class="contact-dropdown-btn" onclick="toggleDropdown()">Select Contact Method ▼</button>
  <div class="contact-dropdown-content" id="contactDropdown">
    <div class="contact-item">
      <strong>Enterprise Inquiries</strong>
      <input type="text" value="biz@galoy.io" readonly onclick="copyToClipboard(this)">
    </div>
    <div class="contact-item">
      <strong>Dev Documentation</strong>
      <input type="text" value="dev.galoy.io" readonly onclick="copyToClipboard(this)">
    </div>
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
function toggleDropdown() {
  document.getElementById("contactDropdown").classList.toggle("show");
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
  padding: 8px;
  background-color: #0d1117;
  border: 1px solid #30363d;
  border-radius: 4px;
  color: #e6edf3;
  font-family: "Source Code Pro", monospace;
  font-size: 13px;
  cursor: pointer;
}

.contact-item input:focus {
  outline: 2px solid #f7931a;
  border-color: #f7931a;
}
</style>

## Additional Resources

### Documentation
Comprehensive technical documentation, deployment guides, and API references.

[View Documentation](https://dev.galoy.io/){: .btn .btn-secondary}

### GitHub
Explore our open-source codebase, contribute to development, or report issues.

[Galoy on GitHub](https://github.com/GaloyMoney){: .btn .btn-secondary}

### Community
Join our developer community for discussions, support, and collaboration.

[Join Community](https://github.com/GaloyMoney/galoy/discussions){: .btn .btn-secondary}

## What to Expect

When you contact us, here's what happens next:

1. **Initial Response**: We'll respond within 24 hours to acknowledge your inquiry
2. **Discovery Call**: Schedule a call to understand your specific needs and timeline
3. **Custom Proposal**: Receive a tailored proposal outlining how Galoy can help
4. **Technical Demo**: See our solutions in action with your use case in mind
5. **Implementation Planning**: Work together to plan your deployment strategy

---

### Frequently Asked Questions

Before reaching out, you might find answers in our comprehensive FAQ section.

[View FAQ](https://dylanwilson21.github.io/markdownsite/faq.html){: .btn .btn-secondary}

---

We look forward to helping you build the future of banking!
