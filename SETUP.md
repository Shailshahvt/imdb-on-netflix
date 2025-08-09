# 🚀 imdb-on-netflix Setup Guide

## Getting Your Free OMDB API Key

### Step 1: Get Free API Key
1. **Visit**: http://www.omdbapi.com/
2. **Click**: "Get a free API key"
3. **Fill out**: The simple form (name, email)
4. **Check email**: You'll receive your API key instantly

### Step 2: Update the Extension
1. **Open**: `content.js`
2. **Find line**: `const OMDB_API_KEY = 'YOUR_OMDB_API_KEY';`
3. **Replace**: `'YOUR_OMDB_API_KEY'` with your actual API key
4. **Save**: The file

### Step 3: Reload Extension
1. **Go to**: `chrome://extensions/`
2. **Find**: imdb-on-netflix extension
3. **Click**: The refresh icon
4. **Test**: Visit Netflix/Hotstar to see real ratings!

## 🎯 What You'll Get

With OMDB API, you'll see **real ratings** from multiple sources:

```
IMDb    ⭐ 8.5    1.2M votes
RT      🍅 89%    Critic
MC      📊 85     Critic
```

### Rating Sources:
- **IMDb**: User ratings (1-10 scale)
- **Rotten Tomatoes**: Critic scores (0-100%)
- **Metascore**: Critic scores (0-100)

## 📊 API Limits
- **Free tier**: 1,000 requests per day
- **Rate limit**: 1 request per second
- **Data**: Complete movie/show information

## 🔧 Troubleshooting

### If ratings don't show:
1. **Check API key**: Make sure it's correct
2. **Check console**: Look for error messages
3. **Test API**: Visit http://www.omdbapi.com/?apikey=YOUR_KEY&t=Inception

### If you hit rate limits:
- The extension has built-in rate limiting
- Wait a few seconds and try again
- Consider upgrading to paid tier for more requests

## 🆓 Free Forever
- **No credit card required**
- **No expiration date**
- **1,000 requests/day** (plenty for personal use)

---

**That's it!** Your extension will now show real, accurate ratings from multiple sources. 🎬✨
