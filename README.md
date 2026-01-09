# EngineersInsight Asset Repository

## Project Overview
This repository serves as a centralized storage location for video assets used in the EngineersInsight platform. It contains manufacturer-specific videos and general application videos that are used across different parts of the platform.

## Repository Structure
```
ei-asset-temp/
└── video/
    ├── Beckhoff/     # Beckhoff-specific video assets
    ├── Hepco/        # Hepco-specific video assets
    ├── igus/         # igus-specific video assets
    ├── Patlite/      # Patlite-specific video assets
    ├── Schneider/    # Schneider-specific video assets
    ├── Sensopart/    # Sensopart-specific video assets
    ├── Siemens/      # Siemens-specific video assets
    └── Yaskawa/      # Yaskawa-specific video assets
```

## Asset Guidelines

### Video Specifications
- Format: MP4
- Resolution: 540p minimum (higher resolutions accepted)
- Codec: H.264
- Audio: AAC (if applicable)
- Maximum file size: 50MB per video

### Naming Conventions
1. Manufacturer-specific videos:
   - Format: `manufacturer_product_name.mp4`
   - Example: `TELEDYN_FLIR_A50_A70_SMART_SENSOR.mp4`

2. Application videos:
   - Format: `application_name_resolution.mp4`
   - Example: `prt2_application_montage_final_540p.mp4`

## Usage Guidelines

### Adding New Assets
1. Create a new branch for your changes
2. Place videos in the appropriate manufacturer directory
3. Follow the naming conventions
4. Submit a pull request for review

### Asset Management
1. Keep file sizes optimized
2. Maintain consistent naming conventions
3. Update this README when adding new manufacturer directories
4. Document any special requirements for specific assets

## Contributing Guidelines
1. Follow the established directory structure
2. Use the specified naming conventions
3. Optimize videos before committing
4. Update documentation for new asset types
5. Include relevant metadata in commit messages

## Support
For questions about asset management:
1. Check this documentation
2. Contact the development team
3. Create an issue in the repository

## License
All assets in this repository are subject to their respective manufacturer's licensing terms. Please ensure you have the necessary rights before using any assets. 