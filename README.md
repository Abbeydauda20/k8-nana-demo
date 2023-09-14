# Tutorial series from "Techworld with Nana" Youtube channel
[https://www.youtube.com/c/techworld-with-nana](https://www.youtube.com/c/techworld-with-nana)


Certainly! Here are 50 commonly used Kubernetes (K8s) commands along with brief explanations for each:

1. `kubectl create deployment <name> --image=<image>`: Create a deployment using a specified container image.

2. `kubectl get pods`: List all pods in the current namespace.

3. `kubectl describe pod <pod-name>`: Show detailed information about a specific pod.

4. `kubectl get svc`: List all services in the current namespace.

5. `kubectl expose deployment <name> --port=<port>`: Create a new service and expose it.

6. `kubectl scale deployment <name> --replicas=<count>`: Scale the number of replicas for a deployment.

7. `kubectl get nodes`: List all nodes in the cluster.

8. `kubectl get deployments`: List all deployments in the current namespace.

9. `kubectl get configmaps`: List all config maps in the current namespace.

10. `kubectl get secrets`: List all secrets in the current namespace.

11. `kubectl create configmap <name> --from-file=<path/to/file>`: Create a config map from a file.

12. `kubectl create secret generic <name> --from-literal=<key>=<value>`: Create a secret with a literal value.

13. `kubectl apply -f <yaml-file>`: Apply a configuration file to create or update resources.

14. `kubectl delete <resource> <name>`: Delete a specific resource.

15. `kubectl get ingress`: List all ingresses in the current namespace.

16. `kubectl describe ingress <name>`: Show detailed information about a specific ingress.

17. `kubectl logs <pod-name>`: View the logs of a specific pod.

18. `kubectl exec -it <pod-name> -- /bin/bash`: Start an interactive shell in a pod.

19. `kubectl get namespaces`: List all namespaces in the cluster.

20. `kubectl create namespace <name>`: Create a new namespace.

21. `kubectl delete namespace <name>`: Delete a namespace and all its resources.

22. `kubectl get events`: List cluster events.

23. `kubectl rollout status deployment/<name>`: Check the status of a deployment rollout.

24. `kubectl rollout history deployment/<name>`: View rollout history for a deployment.

25. `kubectl edit <resource> <name>`: Edit a resource using the default editor.

26. `kubectl apply -f <url>`: Apply a configuration file from a URL.

27. `kubectl get pods -n <namespace>`: List pods in a specific namespace.

28. `kubectl exec -it <pod-name> -n <namespace> -- /bin/bash`: Start an interactive shell in a pod in a specific namespace.

29. `kubectl port-forward <pod-name> <local-port>:<remote-port>`: Forward ports from a pod to your local machine.

30. `kubectl label <resource> <name> <key>=<value>`: Add a label to a resource.

31. `kubectl annotate <resource> <name> <key>=<value>`: Add an annotation to a resource.

32. `kubectl get componentstatuses`: List the health of various cluster components.

33. `kubectl get pods -o wide`: List pods with additional information, including node names.

34. `kubectl describe node <node-name>`: Show detailed information about a specific node.

35. `kubectl get pvc`: List all persistent volume claims.

36. `kubectl get pv`: List all persistent volumes.

37. `kubectl delete pvc <pvc-name>`: Delete a persistent volume claim.

38. `kubectl apply -f <directory>`: Apply all configuration files in a directory.

39. `kubectl top pods`: Show CPU and memory usage of pods.

40. `kubectl rollout restart deployment/<name>`: Restart a deployment.

41. `kubectl apply -f <yaml-file> --dry-run=client`: Check a configuration file for syntax errors without applying it.

42. `kubectl describe service <service-name>`: Show detailed information about a service.

43. `kubectl get endpoints`: List endpoints for services.

44. `kubectl taint nodes <node-name> <key>=<value>:<effect>`: Add a taint to a node.

45. `kubectl uncordon <node-name>`: Remove a node from "cordoned" state.

46. `kubectl create role <name> --resource=<resource> --verb=<verb>`: Create a role.

47. `kubectl create rolebinding <name> --role=<role> --user=<user>`: Create a role binding.

48. `kubectl drain <node-name>`: Safely evict all pods from a node.

49. `kubectl apply -f <yaml-file> --validate=false`: Apply a configuration file, skipping validation.

50. `kubectl proxy`: Start a proxy to access the Kubernetes API.

These commands cover a wide range of common Kubernetes operations. Be sure to replace `<name>`, `<image>`, `<pod-name>`, `<port>`, `<resource>`, `<yaml-file>`, `<key>`, `<value>`, `<url>`, `<namespace>`, `<local-port>`, `<remote-port>`, `<node-name>`, `<pvc-name>`, `<service-name>`, `<role>`, `<user>`, `<effect>`, and `<directory>` with appropriate values as needed in your environment.

