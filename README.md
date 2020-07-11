# No-Blog
### Create a blog with Notion as a CMS  

## ⚠️ **No-Blog is still in production**
1. No nav bar, feel free to implement or place a pull request to add a nav bar  
2. Still a little unstable. Use at your own risk 
3. Deploy to Vercel is broken, working on it currently 

#### Made by [Ben Paine](https://twitter.com/bnpneio)
  
## Get Started

1. Duplicate [this Notion template](https://www.notion.so/b4fdfbc46b534ce58883dd887cae3978?v=50fd8c5289ca4ff0abf6f96209a5bb79) and make it public
2. Copy the page ID for the **Post** page and paste it into `NOTION_BLOG_ID` in the `.env` file  
    - example: if the url is `https://www.notion.so/b4fdfbc46b534ce58883dd887cae3978?v=50fd8c5289ca4ff0abf6f96209a5bb79` the id would be `b4fdfbc46b534ce58883dd887cae3978`
   
![video](./public/videos/id.gif)
 
## Create Blog Post

1. Simply go to the Post page, and click **New**
2. Fill in the Page name, slug, Date, and Author
3. When you're ready, check published
4. Done, the slug and post will appear on the page
## Run Locally

1. Fork the Repository, clone it, and run `npm install`
2. Fill in the `.env` file
3. Run `npm run dev`

## License
[MIT](./LICENSE)
