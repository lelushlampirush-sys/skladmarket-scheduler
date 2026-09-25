# SkladMarket scheduler

This public repository contains only a GitHub Actions dispatcher. It does not
contain marketplace credentials, Telegram credentials, order data, or the
private reporting code.

The workflow calls the `workflow_dispatch` endpoint of the private
`lelushlampirush-sys/skladmarket` repository. Authentication is supplied by the
encrypted `DISPATCH_TOKEN` repository secret.
