# Cache Bug: GET /api/v1/articles

## Description
There is a caching issue with the GET /api/v1/articles endpoint. The response includes Cache-Control: public, max-age=300 and ETag: abc123 headers. Please investigate the caching behavior.