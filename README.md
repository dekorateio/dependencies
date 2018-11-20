# AP4K Dependencies
A Kubernetes/Openshift model uberjar for use with annotation processors

## Rationale

Annotation processors are really useful but can potentially cause classpath related issues.
Gathering the dependencies and shading them inside a `dependecy uberjar` can prevent consuming processrors
from tainting the classpath.
