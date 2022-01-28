# Role deletion test

In Kubernetes, you cannot create or reference a role that represents permissions which the actor does not possess themselves. This is to avoid privilege escalation while allowing RBAC management to be performed by non-superusers.

However, you can delete a role or binding that represents permissions which the actor does not possess themselves.