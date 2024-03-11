# NY State Infrastructure Hub Front-end
Compartmentalized components for [infrastructure.ny.gov](https://infrastructure.ny.gov)

Built with an 11ty shell for local development and component generation by the NYS Digital Service. 
- Each component can be rendered in isolation using render-layout.njk as the template. 
- The resulting code can be copied and pasted into the full html embed option in ArcGIS Hub.
- A netlify workflow has been set up to push changes from `main` to the [demo site](https://nys-infrastructure-hub.netlify.app)
- For the Infrastructure News section: Featured news is the last two weeks followed by archive news, which is 6 weeks back from that. Everything else is purged - keep backups in the _archive directory.
