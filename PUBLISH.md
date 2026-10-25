# Publish (needs Mark's yes: a new public repo under his account)

```
cd /Users/markksantos/Developer/automation/seo-loop/moves-100/datasets/video-editing-service-prices
gh repo create markksantos/video-editing-service-prices --public --source . --description "Video Editing Service Prices (CC BY 4.0) - https://www.markstudios.com/research/video-editing-service-prices" --homepage "https://www.markstudios.com/research/video-editing-service-prices" --push
gh repo edit markksantos/video-editing-service-prices --add-topic dataset --add-topic open-data
```

After it's live: add the repo URL to the page's Dataset `sameAs`/`distribution` and to llms.txt, and submit the page to Google Dataset Search via the existing Dataset schema.
