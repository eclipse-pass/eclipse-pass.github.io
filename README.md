![Eclipse-pass.org homepage](/assets/docs/homepage.png)

## Development

To run this application locally you will require

* [hugo](https://gohugo.io/getting-started/installing/)
* [npm](https://docs.npmjs.com/cli/v7/configuring-npm/install)


You can get the latest dependencies with

```bash
npm install
````

And then launch the site with

```bash
hugo server
```

The local site will be available at

```
http://localhost:1313/
```


## Troubleshooting

### Error building site: POSTCSS: failed

```
Start building sites …
hugo v0.101.0+extended darwin/arm64 BuildDate=unknown
Error: Error building site: POSTCSS: failed to transform "css/app.css"
(text/css). Check your PostCSS installation; install with
"npm install postcss-cli". See https://gohugo.io/hugo-pipes/postcss/:
this feature is not available in your current Hugo version,
see https://goo.gl/YMrWcn for more information
Built in 815 ms
```

Then you must likely have outdated npm modules, re-run `npm install`.
