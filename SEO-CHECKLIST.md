# SEO Checklist & Deployment Guide - Tuontimesta.fi

## ✅ Technical SEO (COMPLETED)

### On-Page SEO
- [x] Optimized title tags with keywords
- [x] Meta descriptions (150-160 characters)
- [x] Relevant keywords in content
- [x] H1-H6 heading hierarchy
- [x] Alt text for all images
- [x] Canonical URLs
- [x] Mobile-responsive design
- [x] Fast loading time (static site)
- [x] Internal linking structure

### Structured Data
- [x] JSON-LD LocalBusiness schema
- [x] Business name, address, phone
- [x] Opening hours
- [x] Geo coordinates (Lahti)
- [x] Service catalog
- [x] Social media links

### Meta Tags
- [x] Open Graph tags (Facebook/LinkedIn)
- [x] Twitter Card tags
- [x] Robots meta tag
- [x] Viewport meta tag
- [x] Charset declaration

### Files Created
- [x] robots.txt
- [x] sitemap.xml
- [x] .htaccess (Apache config)

---

## 📋 Post-Deployment Checklist

### 1. Upload to VPS
```bash
# Upload files to server
scp -r * user@server:/var/www/tuontimesta.fi/

# Or use FTP/SFTP client
# Make sure to upload:
# - index.html
# - styles.css
# - script.js
# - images/ folder
# - robots.txt
# - sitemap.xml
# - .htaccess
```

### 2. SSL Certificate
- [ ] Install SSL certificate (Let's Encrypt recommended)
- [ ] Verify HTTPS works
- [ ] Test HTTP to HTTPS redirect

### 3. Domain Configuration
- [ ] Verify DNS points to VPS
- [ ] Choose www vs non-www (update .htaccess accordingly)
- [ ] Test both www and non-www redirect correctly

### 4. Submit to Search Engines

#### Google Search Console
- [ ] Add property: https://www.tuontimesta.fi
- [ ] Verify ownership (HTML file method or DNS)
- [ ] Submit sitemap: https://www.tuontimesta.fi/sitemap.xml
- [ ] Request indexing for homepage
- [ ] Monitor for errors

#### Bing Webmaster Tools
- [ ] Add site
- [ ] Verify ownership
- [ ] Submit sitemap
- [ ] Request indexing

### 5. Google My Business (Already exists)
- [ ] Update business information if needed
- [ ] Add link to new website
- [ ] Add photos from gallery
- [ ] Verify NAP (Name, Address, Phone) matches website exactly
- [ ] Enable messaging if not enabled
- [ ] Post updates regularly

### 6. Analytics Setup
- [ ] Install Google Analytics 4
- [ ] Set up conversion tracking (contact form submissions)
- [ ] Set up goals (phone clicks, email clicks)
- [ ] Monitor traffic sources

---

## 🚀 SEO Growth Strategy

### Immediate Actions (Week 1-2)
1. **Submit to search engines** (see checklist above)
2. **Verify all links work** - check 404 errors
3. **Test mobile performance** - Google PageSpeed Insights
4. **Monitor Google Search Console** - watch for indexing issues

### Short-term (Month 1-3)
1. **Create content**
   - Blog post: "5 asiat joita tietää ennen auton maahantuontia"
   - Blog post: "Sähköautojen maahantuonti - mitä huomioida"
   - Customer case studies

2. **Build backlinks**
   - Local business directories (fonecta.fi, etc.)
   - Industry forums (autolla.net participation)
   - Partner websites
   - Social media profiles

3. **Social media activity**
   - Regular Instagram posts
   - Share success stories
   - Behind-the-scenes content
   - Engage with followers

4. **Collect reviews**
   - Ask satisfied customers for Google reviews
   - Respond to all reviews (positive and negative)

### Medium-term (Month 3-6)
1. **Content marketing**
   - More blog posts (2-4 per month)
   - Video content (process walkthrough)
   - FAQ section expansion

2. **Local SEO**
   - Get listed in local directories
   - Local press releases
   - Participate in local events

3. **Monitor and adjust**
   - Check rankings for key terms
   - Analyze which content performs best
   - Adjust strategy based on data

---

## 🎯 Target Keywords (Priority Order)

### Primary Keywords
1. autojen maahantuonti
2. autojen tuonti saksasta
3. saksalaiset autot
4. auton tuonti
5. autojen maahantuonti lahti

### Secondary Keywords
1. mercedes tuonti
2. bmw tuonti
3. sähköautojen tuonti
4. sähköauto maahantuonti
5. käytetyt autot saksasta

### Long-tail Keywords
1. autojen maahantuonti saksasta hinta
2. kuinka tuoda auto saksasta
3. autojen tuonti saksasta kokemuksia
4. sähköauton tuonti suomeen
5. mercedes farmari maahantuonti

---

## 📊 Metrics to Track

### Weekly
- Google Search Console impressions
- Click-through rate (CTR)
- Phone calls from website
- Contact form submissions

### Monthly
- Organic traffic growth
- Keyword rankings
- Backlink growth
- Conversion rate

### Quarterly
- ROI from SEO efforts
- Customer acquisition cost
- Revenue from web leads

---

## 🔧 Technical Monitoring

### Regular Checks (Monthly)
- [ ] Check for broken links
- [ ] Verify all images load
- [ ] Test mobile responsiveness
- [ ] Check page load speed
- [ ] Review Google Search Console errors
- [ ] Check robots.txt accessibility
- [ ] Verify sitemap is up to date

### Updates Needed
- [ ] Update lastmod dates in sitemap.xml when content changes
- [ ] Update copyright year in footer (already 2026)
- [ ] Add new content to sitemap when created
- [ ] Refresh gallery images regularly

---

## 🆘 Troubleshooting

### Site not indexing?
1. Check robots.txt is accessible: https://www.tuontimesta.fi/robots.txt
2. Check sitemap is accessible: https://www.tuontimesta.fi/sitemap.xml
3. Submit URL for indexing in Google Search Console
4. Check for manual actions in Search Console
5. Verify canonical URLs are correct

### Rankings not improving?
1. Check keyword competition
2. Analyze competitor content
3. Build more backlinks
4. Improve content quality
5. Focus on user experience

### Traffic but no conversions?
1. Make contact info more prominent
2. Add social proof (reviews, testimonials)
3. Improve call-to-action buttons
4. Reduce friction in contact process
5. Add live chat or chatbot

---

## 📞 Contact for SEO Questions

For technical SEO questions or issues, refer to:
- Google Search Console Help
- Bing Webmaster Tools Support
- Web hosting provider support (for server issues)

---

**Last Updated:** 2026-02-12
**Next Review:** Monthly or when major changes made
