# LM2 Webview

This interactive viewer enables you to explore the <a href="https://www.lymemind.org/">LymeMIND2</a> patient cohort in gene expression space. Each point on the map corresponds to a participant where the position of each participant was computed based on a UMAP projection of their PMBC mRNA RNA-seq expression vector. Enrichment analysis is applied to explore enriched terms for each cluster. You can explore these enriched terms by clicking on a cluster to review the table below. These enrichment results were computed by performing differential expression between clusters and using the most significantly up and down regulated genes to query with <a href="http://maayanlab.cloud/Enrichr/">Enrichr</a>. The <a href="https://maayanlab.github.io/react-scatter-board/">react scatter board widget</a> is used to render this plot.


## Development

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
