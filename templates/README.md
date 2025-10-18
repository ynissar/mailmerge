# Email Templates

This directory contains email templates for networking and job referral outreach.

## Available Templates

### general_template.txt
General LinkedIn outreach template.

**Required fields:** `name`, `email`, `company`

### wealthsimple_template.txt
Template for Wealthsimple alumni.

**Required fields:** `name`, `email`

### western_template.txt
Template for Western University alumni.

**Required fields:** `name`, `email`, `company`

### ivey_template.txt
Template for Ivey Business School alumni.

**Required fields:** `name`, `email`, `company`

### newgrad_template.txt
Template for fellow recent graduates.

**Required fields:** `name`, `email`, `company`

## Usage

```csv
email,name,company,template
engineer@google.com,Sarah,Google,western_template.txt
recruiter@wealthsimple.com,Mike,Wealthsimple,wealthsimple_template.txt
dev@stripe.com,Emily,Stripe,general_template.txt
```

All templates include the resume attachment: `../mailmerge/attachments/Yusuf Nissar Resume.pdf`
