FROM alpine

# Couple curl commands to demonstrate that metadata is exposed
CMD curl "http://metadata.google.internal/computeMetadata/v1/instance/disks/0/" -H "Metadata-Flavor: Google"
CMD curl "http://metadata.google.internal/computeMetadata/v1/instance/tags" -H "Metadata-Flavor: Google"
