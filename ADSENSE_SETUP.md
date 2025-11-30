# Google AdSense Setup Instructions for City Runner Game

## Current Status
✅ Game is live at: https://sarthakwebsite26012000-dot.github.io/city-runner-game/
✅ AdSense code placeholders are integrated in index.html
⚠️ You need to complete AdSense account setup and replace placeholder codes

## Step 1: Create Google AdSense Account

1. Go to https://www.google.com/adsense
2. Click "Sign up for a new AdSense account"
3. Fill in the required information:
   - Your website URL: https://sarthakwebsite26012000-dot.github.io/city-runner-game/
   - Your email address (use sarthakwebsite26012000@gmail.com)
   - Country: Select your country
4. Accept the AdSense Terms and Conditions
5. Submit your application

## Step 2: AdSense Requirements (MUST MEET THESE)

- ✓ You must be 18+ years old
- ✓ Website must have original, high-quality content
- ✓ Website must have sufficient content
- ✓ Website must comply with AdSense Program Policies
- ✓ Website should have organic traffic (real visitors)
- ⚠️ Need to add: About, Privacy Policy, and Contact pages

## Step 3: Get Your AdSense Publisher ID

Once your AdSense account is approved (takes 2-4 weeks):

1. Sign in to your AdSense account
2. Click on "Ads" in the left menu
3. Click "Get code"
4. You'll see code like: `<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-1234567890123456"></script>`
5. Copy your Publisher ID (the numbers after ca-pub-)

## Step 4: Replace Placeholder Codes

In your index.html file, replace these placeholders:

### Replace Line 40-41 (in <head> section):
**Current:**
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

**Replace with:**
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR-ACTUAL-ID" crossorigin="anonymous"></script>
```

### Replace Lines 238 and 239 (Ad Unit):
**Current:**
```html
data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
data-ad-slot="YYYYYYYYYY"
```

**Replace with your actual values:**
```html
data-ad-client="ca-pub-YOUR-ACTUAL-ID"
data-ad-slot="YOUR-AD-SLOT-ID"
```

## Step 5: Create Ad Units

1. In AdSense dashboard, click "Ads" → "By ad unit" → "Display ads"
2. Create a new display ad unit
3. Name it "City Runner Game Ad"
4. Choose "Responsive" size
5. Click "Create"
6. Copy the ad unit code
7. Get the data-ad-slot value from the code
8. Update your index.html with this ad-slot ID

## Step 6: Wait for Approval and Verification

1. After updating codes, AdSense will review your site
2. They will check:
   - Content quality
   - Policy compliance
   - Proper ad placement
3. This review takes a few days to 2-4 weeks
4. You'll receive an email when approved

## Step 7: Start Earning!

Once approved:
- Ads will automatically display on your game
- You earn money when visitors:
  - View ads (impressions)
  - Click on ads (CPC - Cost Per Click)
- Payment threshold: $100 USD
- Payment methods: Bank transfer, check, or other options based on your country

## Important Tips for Higher Earnings

1. **Drive Traffic:** More visitors = more ad views = more money
   - Share your game on social media
   - Post on gaming forums
   - Share on Reddit (r/WebGames, r/incremental_games)
   - Create YouTube videos about your game

2. **Optimize Ad Placement:**
   - Place ads at natural breaks
   - Don't place too many ads (violates policy)
   - Current placement (below game) is good

3. **Improve Game Content:**
   - Add more levels
   - Add leaderboards
   - Add sharing features
   - Regular updates keep players coming back

4. **Allowed Traffic Sources:**
   ✓ Organic search
   ✓ Social media shares
   ✓ Direct traffic
   ✗ Paid traffic (may violate AdSense policy)
   ✗ Click bots (will get you banned)

## Expected Earnings

Realistic expectations for a game website:
- RPM (Revenue per 1000 views): $0.50 - $5.00 USD
- With 1,000 daily visitors: $15-150/month
- With 10,000 daily visitors: $150-1,500/month

*Note: Actual earnings vary based on visitor location, ad engagement, and niche.*

## Common Issues and Solutions

### Issue: "Ads not showing"
**Solutions:**
- Wait 24-48 hours after code update
- Clear browser cache
- Check if AdSense account is fully approved
- Verify ad code is correct
- Check browser console for errors

### Issue: "Account suspended"
**Causes:**
- Invalid click activity
- Violating content policies
- Insufficient content
**Prevention:**
- Never click your own ads
- Don't ask others to click
- Follow all AdSense policies

### Issue: "Low earnings"
**Solutions:**
- Increase traffic
- Improve content quality
- Better ad placement
- Target higher-paying countries (US, UK, Canada)

## Additional Monetization Options

Besides AdSense, consider:
1. **Google H5 Games Ads Beta** (for HTML5 games specifically)
2. **Affiliate marketing** (promote gaming products)
3. **Sponsorships** (get sponsors for your game)
4. **Premium version** (ad-free paid version)
5. **In-game purchases** (cosmetics, power-ups)

## Resources

- AdSense Help Center: https://support.google.com/adsense
- AdSense Policies: https://support.google.com/adsense/answer/48182
- AdSense Community: https://support.google.com/adsense/community

## Support

If you need help:
1. Check AdSense Help Center
2. Visit AdSense Community Forum
3. Contact AdSense Support (only after account creation)

---

**Last Updated:** November 30, 2025
**Game URL:** https://sarthakwebsite26012000-dot.github.io/city-runner-game/
**Repository:** https://github.com/sarthakwebsite26012000-dot/city-runner-game
