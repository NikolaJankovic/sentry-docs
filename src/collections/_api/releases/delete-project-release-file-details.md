---
{
  "authentication": "required", 
  "description": "Permanently remove a file from a release.This will also remove the physical file from storage.", 
  "example_request": "DELETE /api/0/projects/the-interstellar-jurisdiction/pump-station/releases/88dc638c8ccb84e5b7c750da882232aa1b394ac1/files/1/ HTTP/1.1\nHost: sentry.io\nAuthorization: Bearer {base64-encoded-key-here}", 
  "example_response": "HTTP/1.1\nContent-Length: 0\nX-XSS-Protection: 1; mode=block\nContent-Language: en\nX-Content-Type-Options: nosniff\nVary: Accept-Language, Cookie\nAllow: GET, PUT, DELETE, HEAD, OPTIONS\nX-Frame-Options: deny", 
  "method": "DELETE", 
  "parameters": null, 
  "path_parameters": [
    {
      "description": "the slug of the organization the release belongs to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the slug of the project to delete the file of.", 
      "name": "project_slug", 
      "type": "string"
    }, 
    {
      "description": "the version identifier of the release.", 
      "name": "version", 
      "type": "string"
    }, 
    {
      "description": "the ID of the file to delete.", 
      "name": "file_id", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 21, 
  "title": "Releases"
}
---