# config_bundle_example
Example(s) of Master Config Bundles for Config as Code

#### Export example YAML files
Export YAML files from an existing master by adding `core-casc-export` to URL

#### Store this to OC via a freestyle job like this:
```
rm -rf config_bundle_example/
rm -rf $JENKINS_HOME/jcasc-bundles-store/*
 
git clone https://github.com/BillGarrett/config_bundle_example
cd config_bundle_example
mv bundlemaster $JENKINS_HOME/jcasc-bundles-store/
```
