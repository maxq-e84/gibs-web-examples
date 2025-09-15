# Known Issues

- Web Mercator endpoints return a blank map at zoom level zero due to a bug in the tiling software.
- Some mapping libraries may fetch tiles outside the tile matrix boundaries. GIBS returns error codes for these requests.
- Gaps may appear between map tiles in Leaflet. Use the workaround discussed in [Leaflet Issue #3575](https://github.com/Leaflet/Leaflet/issues/3575).

## Troubleshooting

If you encounter issues:
- Check that your layer parameters are correct.
- Ensure API keys are set for Bing or Google Maps.
- Use the recommended library versions (see [Platform-Specific Notes](Platform-Specific-Notes.md)).
- For further help, contact [earthdata-support@nasa.gov](mailto:earthdata-support@nasa.gov).