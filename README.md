# Curriculum Builder

Tools to build and visualize study plans for DTU MSc programs in **Sustainable Energy Systems (SES)** and **Sustainable Energy Technologies (SET)**.

## Overview

The Curriculum Builder is a collection of interactive web-based tools designed to help students and advisors explore and plan their academic journey through the Sustainable Energy MSc programs at the Technical University of Denmark (DTU). These tools provide comprehensive visualizations of course structures, program requirements, and personalized study plan management.

## Features

### 📚 Study Plan Builder
Interactive tools to create and customize personalized study plans:
- **SES Study Plan Builder** - Build custom study plans for the Sustainable Energy Systems program
- **SET Study Plan Builder** - Build custom study plans for the Sustainable Energy Technologies program
- Drag-and-drop course selection
- Real-time validation against program requirements
- Export and save custom study plans

### 🔍 Study Plan Explorer
Browse and analyze existing study plans:
- **SES Study Plan Explorer** - Explore curated study plans for SES
- **SET Study Plan Explorer** - Explore curated study plans for SET
- Visualize course sequences and dependencies
- Compare different program pathways
- Filter courses by semester, specialization, and elective category

### 🗺️ Campus Visualization
Geographic visualization of programs and resources:
- **SES Campus Explorer** - Campus-based visualization for SES program
- **SET Campus Explorer** - Campus-based visualization for SET program
- Interactive campus maps
- Location information for course facilities
- Resource availability across DTU campus

### 📋 Example Study Plans
Pre-configured study plans for quick reference:
- **Fall Study Plans** - Example schedules for fall semester entry
  - SES Fall Examples
  - SET Fall Examples
- **Spring Study Plans** - Example schedules for spring semester entry
  - SES Spring Examples
  - SET Spring Examples
- Ready-to-use templates for common specializations
- Peer-reviewed curriculum paths

## Quick Start

### Accessing the Tools

All tools are available as standalone HTML files. Simply open any of the following files in a modern web browser:

| Program | Tool | File |
|---------|------|------|
| **SES** | Builder | `SES-study-plan-builder.html` |
| **SES** | Explorer | `SES-study-plan-explorer.html` |
| **SES** | Campus Visualization | `SES-study-plan-explorer-campus-visualization.html` |
| **SES** | Fall Examples | `SES-example-study-plans-fall.html` |
| **SES** | Spring Examples | `SES-example-study-plans-spring.html` |
| **SET** | Builder | `SET-study-plan-builder.html` |
| **SET** | Explorer | `SET-study-plan-explorer.html` |
| **SET** | Campus Visualization | `SET-study-plan-explorer-campus-visualization.html` |
| **SET** | Fall Examples | `SET-example-study-plans-fall.html` |
| **SET** | Spring Examples | `SET-example-study-plans-spring.html` |

### Browser Requirements

- Modern web browser with JavaScript enabled
- Chrome, Firefox, Safari, or Edge (latest versions recommended)
- Screen resolution: 1024x768 or higher for optimal experience

## Programs Supported

### Sustainable Energy Systems (SES)
A comprehensive MSc program focusing on the integrated design and optimization of sustainable energy systems. This program combines engineering fundamentals with advanced topics in renewable energy, grid management, and sustainability assessment.

**Key Focus Areas:**
- Energy systems planning and optimization
- Renewable energy integration
- Smart grids and energy storage
- Life cycle assessment
- Techno-economic analysis

### Sustainable Energy Technologies (SET)
A specialized MSc program emphasizing specific sustainable energy technologies and their practical implementation. This program provides in-depth knowledge of modern energy conversion technologies and their deployment.

**Key Focus Areas:**
- Photovoltaic systems
- Wind energy technology
- Energy storage solutions
- Thermal systems
- Power electronics

## File Structure

```
curriculum-builder/
├── README.md                                          # This file
├── LICENSE                                            # GNU GPLv3 License
├── SES-study-plan-builder.html                        # SES builder tool
├── SES-study-plan-explorer.html                       # SES explorer tool
├── SES-study-plan-explorer-campus-visualization.html  # SES campus view
├── SES-example-study-plans-fall.html                  # SES fall examples
├── SES-example-study-plans-spring.html                # SES spring examples
├── SET-study-plan-builder.html                        # SET builder tool
├── SET-study-plan-explorer.html                       # SET explorer tool
├── SET-study-plan-explorer-campus-visualization.html  # SET campus view
├── SET-example-study-plans-fall.html                  # SET fall examples
└── SET-example-study-plans-spring.html                # SET spring examples
```

## Usage Guide

### For Students

1. **Choosing Your Program**
   - Determine whether you're pursuing SES or SET
   - Start with the example study plans for your entry semester

2. **Exploring Options**
   - Use the Study Plan Explorer to understand program structure
   - Review available courses and prerequisites
   - Examine the campus visualization to understand class locations

3. **Building Your Plan**
   - Open the Study Plan Builder for your program
   - Select courses based on your interests and requirements
   - Verify all program requirements are met
   - Save your plan for reference

### For Academic Advisors

- Use the explorers to guide students through program options
- Reference pre-built examples when discussing typical pathways
- Combine builder tools with campus visualization for logistics planning
- Compare student plans against program requirements

### For Program Administrators

- Use these tools for curriculum management and planning
- Verify students follow program requirements
- Analyze program outcomes and course sequences
- Support recruitment with interactive program demonstrations

## Features in Detail

### Course Management
- View comprehensive course descriptions
- Check prerequisites and dependencies
- Understand credit requirements (ECTS)
- See course scheduling across semesters

### Customization
- Create personalized study plans
- Mix and match elective courses
- Explore different specialization pathways
- Adapt plans to individual career goals

### Validation
- Automatic checking against program requirements
- Warning system for prerequisite mismatches
- ECTS credit tracking
- Specialization requirement verification

### Visualization
- Interactive course networks
- Timeline-based semester planning
- Geographic campus layout
- Dependency graphs

## System Requirements

- **Operating System:** Windows, macOS, or Linux
- **Browser:** Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Internet Connection:** Optional (tools work offline once loaded)
- **Screen Resolution:** Minimum 1024x768 (recommended 1920x1080)

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

This means:
- ✅ Free to use, modify, and distribute
- ✅ Must include license notice
- ✅ Must disclose source code
- ✅ Same license applies to modifications

## Contributing

We welcome contributions to improve these tools! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit with clear messages (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

### Development Notes

- Tools are built as standalone HTML files for easy deployment
- No external dependencies required for production
- JavaScript-based for client-side processing
- Responsive design for multiple screen sizes

## Troubleshooting

### Common Issues

**Q: Tools don't load or display incorrectly**
- Ensure JavaScript is enabled in your browser
- Clear browser cache and reload
- Try a different browser
- Check that cookies are allowed

**Q: Can't save my study plan**
- Use browser's built-in save functionality (Ctrl+S or Cmd+S)
- Export plan as PDF if available
- Check browser's local storage limits

**Q: Courses appear missing or outdated**
- Tools may need to be updated with new course information
- Contact program administration for curriculum updates
- Clear cache to ensure latest version is loaded

## Support & Feedback

For issues, questions, or suggestions:
- Open an issue on the project repository
- Contact DTU program administration
- Check program website for additional resources

## Acknowledgments

Developed for DTU's Sustainable Energy MSc Programs (SES & SET). Special thanks to all students, advisors, and faculty who provided feedback during development.

## Roadmap

Future enhancements may include:
- Mobile app versions
- Integration with DTU student portal
- Real-time course availability updates
- Advanced analytics for program outcomes
- Peer network visualization
- Course recommendation engine

## Version History

- **v1.0** - Initial release with SES and SET programs
- **v1.1** - Added campus visualization tools
- **v1.2** - Enhanced explorer with filtering and search

---

**Last Updated:** March 2026  
**Status:** Active Development  
**Maintainer:** DTU Energy Systems Group

