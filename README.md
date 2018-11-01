# Daimo Karaf Bundle Project

This project generates a (Karaf Archive) bundle containing daimo processor services to be deployed on a [Apache Karaf](https://karaf.apache.org/) instance. These [OSGI](https://www.osgi.org/) services are made available by a [Jetty](https://www.eclipse.org/jetty/) server via SOAP. The corrsponding WSDL definitions are automatically generated and published to a [Zookeeper](https://zookeeper.apache.org/) instance by [Apache CXF](http://cxf.apache.org/). These published WSDL definitions are then used by the Daimo Remote library access the services remotely.

# License

Copyright (c) 2017-2018 brewlabs SAS

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
