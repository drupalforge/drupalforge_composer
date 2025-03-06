<h1>
    <a href="https://www.drupalforge.org/">
        <img src="drupalforge.svg" alt="Drupal Forge" height="100px" />
    </a>
</h1>

This is a template for creating a [Drupal Forge](https://www.drupalforge.org)
app that fetches all its code with Composer, then installs Drupal with a default
admin password of _admin_. It is optimized for fast deployment with
[DevPanel](https://www.devpanel.com). DevPanel deployment files are in the
[.devpanel](.devpanel) directory. This repository is also configured to be run
locally using [DDEV](https://ddev.com).

For even faster deployment, click the Actions tab after you have created your
repository in GitHub and add the Drupal Forge Docker Publish Workflow. This
will generate a Docker image whenever a commit is pushed to the main, develop,
or test/* branches. Drupal will be fully deployed in this Docker image,
reducing the time required to launch the site.
