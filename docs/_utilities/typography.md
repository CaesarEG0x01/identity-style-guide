---
title: Typography
lead: >
  When writing longform text (a page like this), wrap the text in <code class="text-no-wrap">div.usa-prose</code> to activate these styles.
redirect_from:
  - /typography/
---

## Display, headings, and lead

Use <code class="text-no-wrap">div.usa-prose</code> to indicate that the immediately containing headings and paragraphs should be considered a longform text document.

<div class="border-base-light border-left-1 padding-3 usa-prose">
  <div class="usa-display">How Login.gov keeps personal information private <span class="text-no-wrap text-secondary">(div.usa-display)</span></div>

  <p class="usa-intro">Login.gov encrypts the personal information of each user separately, using a unique value generated from each user’s password. Our encryption method works like a safe deposit box in a bank vault. Only the user has the key. Only the user can open the box to reveal the contents. Only the user knows the password, and only the user can decrypt their information. <span class="text-no-wrap text-secondary">(p.usa-intro)</span></p>

  <h1>The vault <span class="text-no-wrap text-secondary">(h1)</span></h1>

  <p>It’s hard to break into the “vault” or database. Login.gov implements the latest National Institute of Standards and Technology (NIST) standards for secure authentication and verification. Our plans for ongoing security include regular penetration testing and external security reviews.</p>

  <h2>The safe deposit box <span class="text-no-wrap text-secondary">(h2)</span></h2>

  <p>Individual accounts get a double layer of security. We require two-factor authentication as well as strong passwords that meet new NIST requirements. Two factor authentication requires that you login with your password and a code that we send to your phone.</p>

  <p>We will evaluate and implement new authentication methods as they become widely available to make sure that Login.gov remains accessible and secure.</p>

  <h3>Your personal key <span class="text-no-wrap text-secondary">(h3)</span></h3>

  <p>Encrypting personal data separately means that Login.gov cannot share any information with other government entities without users’ permission. Not even database administrators can decrypt a user’s personal information without the user’s password.</p>

  <h4>Join us on GitHub <span class="text-no-wrap text-secondary">(h4)</span></h4>

  <p>We welcome external review of our privacy-protection measures. All of our code is available for public inspection in an open-source repository. Our goal: make sure that at every step users know their privacy is being protected by design.</p>

  <h5>More information on Login.gov <span class="text-no-wrap text-secondary">(h5)</span></h5>

  <p>For more information, please visit the Login.gov Help Center or contact us. You can also visit our open-source repository.</p>

  <h6>Simple and secure <span class="text-no-wrap text-secondary">(h6)</span></h6>

  <p>Dedicated teams of design and security experts will continuously improve it.</p>

  <ul>
    <li>We welcome external review of our privacy-protection measures. All of our code is available for public inspection in an open-source repository. Our goal: make sure that at every step users know their privacy is being protected by design.</li>
    <li>For more information, please visit the Login.gov Help Center or contact us. You can also visit our open-source repository.</li>
    <li>Dedicated teams of design and security experts will continuously improve it.</li>
  </ul>
</div>
