# vision-validation-framework

Framework for validating image-derived metadata using vision-capable LLMs
(Amazon Nova, Claude) as a cross-check against traditional OCR (Rekognition,
EasyOCR, Textract). Includes drift review (does the poster image actually
match the catalog title?), OCR accuracy scoring, and alternative-title
cross-referencing (IMDb AKAs, TMDB alternative_titles) to separate real
data errors from false positives.

Part of the [Pulp Analytics](https://github.com/pulp-analytics) horror poster
analysis project ("The Anatomy of Fear").

## License

MIT — see [LICENSE](LICENSE).
