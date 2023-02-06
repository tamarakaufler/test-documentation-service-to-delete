# test-documentation-service-to-delete

This repo is an example of how a Software Architecture Documentation repository, which is used in conjunction with the Backstage Portal framework, could be organised.

- catalog-info.yaml ... Backstage configuration
- mkdocs.yml .......... Backstage TechDocs configuration
- docs directory ...... contains all documentation (md format) to be available in the Porta

## Documentation

By default Backstage expects markdown pages to be found in a directory called _docs_. Backstage takes advantage of _mkdocs_, a static site generator geared towards building project documentation.

### Software Architecture Documentation

The approach to writing the documentation follows __arc42__ (documentation structure) and __C4 model__ (diagramming) approaches. The _docs_ directory contains a page about the overall system architecture and subdirectories with the next level subsystems. The pages are arc42 templates that are filled in with the required information.

https://github.com/tamarakaufler/test-documentation-service-to-delete/blob/master/docs/README.md
