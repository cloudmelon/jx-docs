---
date: 2019-06-02T19:49:56Z
title: "jx cloudbees"
slug: jx_cloudbees
url: /commands/jx_cloudbees/
---
## jx cloudbees

Opens the CloudBees app for Kubernetes for visualising CI/CD and your environments

### Synopsis

Opens the CloudBees UI in a browser. 

Which helps you visualise your CI/CD pipelines, apps, environments and teams. 

For more information please see https://www.cloudbees.com/blog/want-help-build-cloudbees-kubernetes-jenkins-x

```
jx cloudbees [flags]
```

### Examples

```
  # Open the core dashboard in a browser
  jx cloudbees
  
  # Print the Jenkins X console URL but do not open a browser
  jx console -u
```

### Options

```
  -h, --help   help for cloudbees
  -u, --url    Only displays and the URL and does not open the browser
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx cloudbees pipeline](/commands/jx_cloudbees_pipeline/)	 - Opens the CloudBees Pipeline page for visualising CI/CD

###### Auto generated by spf13/cobra on 2-Jun-2019
