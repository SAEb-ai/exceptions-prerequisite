## Description

This folder is first used to create a policy exception(policy_exception.yaml file) which grants an exception to a Pod or Deployment named important-app created in the delta namespace against 
limit-containers-per-pod policy.

## Expected Behavior

allowed_resource.yaml should be accepted and blocked_resource.yaml should be blocked.

