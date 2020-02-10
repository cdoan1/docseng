# docseng

Naming convent scheme

| "proto" | "OCP release" | "variant" | "ipv4/6" | "iteration" | name |
|---------|---------------|-----------|----------|-------------|------|
| proto | 43 | hop   | 4 | 2 | proto43hop4-2 |
| proto | 43 | hop   | 6 | 1 | proto43hop6-1 |
| proto | 42 | mfest | 4 | 1 | proto42mfest4-1 |
| proto | 43 | mfest | 6 | 1 | proto43mfest6-1 |
| proto | 43 | mfest | 4 | 1 | proto43mfest4-1 |
| proto | 42 | incep | 4 | 1 | proto42incp4-1 |

# Automation Deployment

1. Using `bootstrap` and `inception` deploy from quay.io the current level of code, `3.3.0`
   * one difference is that the helm charts are still coming from artifactory
   * no changes to the `boostrap` code base


2. Using `bootstrap`, swap out the `inception` job for the `manifest` job.
   * steps to create the `manifest` job.
     * create a Dockerfile for the `manifest` repo
     * 
