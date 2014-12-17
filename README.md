Devoxx 2014 Uni Session
-----------------------
Create an account at http://openshift.redhat.com/


Install with one click
----------------------
[![One click install OpenShift](http://launch-shifter.rhcloud.com/launch/light/One click
install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-preso-devoxx-masteringxpaas.git&name=masteringxpaas)

Manual setup on OpenShift
-------------------------
Create a PHP application

    rhc app create masteringxpaas -t php-5.4 --from-code git://github.com/eschabell/openshift-preso-devoxx-masteringxpaas.git

That's it, you can now start your workshop at:

    http://masteringxpaas-$your_domain.rhcloud.com

![Cover Slide](https://raw.githubusercontent.com/eschabell/openshift-preso-devoxx-masteringxpaas/master/cover.png)
