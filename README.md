# Veyra demo assets

Static image assets for the Veyra hackathon demo, published so the application
backend can fetch them over HTTPS with stable, untransformed bytes.

- `catalog/` — 40 Veyra-owned generated-original garment images
- `roster/` — 4 Veyra-owned synthetic model images

These are delivery artifacts. Bytes must not be re-encoded: the try-on worker
pins each object to a recorded SHA-256 and refuses any mismatch.
