# vision-validation-framework

Framework for validating image-derived metadata using vision-capable LLMs
(Amazon Nova, Claude) as a cross-check against traditional OCR (Rekognition,
EasyOCR, Textract). Includes drift review (does the poster image actually
match the catalog title?), OCR accuracy scoring, and alternative-title
cross-referencing (IMDb AKAs, TMDB alternative_titles) to separate real
data errors from false positives.

Part of the [Pulp Analytics](https://github.com/pulp-analytics) horror poster
analysis project, published as [What Fear Looks Like](https://pulpanalytics.com/) (working title:
"The Anatomy of Fear").

**Status: no code here yet.** The vision-LLM cross-checks described above
were built and run inside
[poster-corpus-validation](https://github.com/pulp-analytics/poster-corpus-validation)
(see its [docs/RESULTS.md](https://github.com/pulp-analytics/poster-corpus-validation/blob/main/docs/RESULTS.md));
this repo is where a reusable version would live.

## License

MIT — see [LICENSE](LICENSE).
