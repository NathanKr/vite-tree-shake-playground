<h2>Does vite has tree shaking</h2>
<p>Yes. We have min function in utils but because it is not used it will not appear dist directory</p>
<p>However, you will see this function in dist if you will call min in main.ts and 'npm run build' </p>