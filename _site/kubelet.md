### Kubelet Events

[kubelet/events/event.go](https://github.com/kubernetes/kubernetes/blob/master/pkg/kubelet/events/event.go)

### Container Events

  ```
  CreatedContainer        = "Created"
  StartedContainer        = "Started"
  FailedToCreateContainer = "Failed"
  FailedToStartContainer  = "Failed"
  KillingContainer        = "Killing"
  PreemptContainer        = "Preempting"
  BackOffStartContainer   = "BackOff"
  ExceededGracePeriod     = "ExceededGracePeriod"
  ```

### Pod Events

  ```
  FailedToKillPod                = "FailedKillPod"
  FailedToCreatePodContainer     = "FailedCreatePodContainer"
  FailedToMakePodDataDirectories = "Failed"
  NetworkNotReady                = "NetworkNotReady"
  ```
  
### Image Events

  ```
  PullingImage            = "Pulling"
  PulledImage             = "Pulled"
  FailedToPullImage       = "Failed"
  FailedToInspectImage    = "InspectFailed"
  ErrImageNeverPullPolicy = "ErrImageNeverPull"
  BackOffPullImage        = "BackOff"
  ```

### Kubelet Events

  ```
  NodeReady                            = "NodeReady"
  NodeNotReady                         = "NodeNotReady"
  NodeSchedulable                      = "NodeSchedulable"
  NodeNotSchedulable                   = "NodeNotSchedulable"
  StartingKubelet                      = "Starting"
  KubeletSetupFailed                   = "KubeletSetupFailed"
  FailedAttachVolume                   = "FailedAttachVolume"
  FailedMountVolume                    = "FailedMount"
  VolumeResizeFailed                   = "VolumeResizeFailed"
  VolumeResizeSuccess                  = "VolumeResizeSuccessful"
  FileSystemResizeFailed               = "FileSystemResizeFailed"
  FileSystemResizeSuccess              = "FileSystemResizeSuccessful"
  FailedMapVolume                      = "FailedMapVolume"
  WarnAlreadyMountedVolume             = "AlreadyMountedVolume"
  SuccessfulAttachVolume               = "SuccessfulAttachVolume"
  SuccessfulMountVolume                = "SuccessfulMountVolume"
  NodeRebooted                         = "Rebooted"
  ContainerGCFailed                    = "ContainerGCFailed"
  ImageGCFailed                        = "ImageGCFailed"
  FailedNodeAllocatableEnforcement     = "FailedNodeAllocatableEnforcement"
  SuccessfulNodeAllocatableEnforcement = "NodeAllocatableEnforced"
  SandboxChanged                       = "SandboxChanged"
  FailedCreatePodSandBox               = "FailedCreatePodSandBox"
  FailedStatusPodSandBox               = "FailedPodSandBoxStatus"
  FailedMountOnFilesystemMismatch      = "FailedMountOnFilesystemMismatch"
  ```

### Image manager Events

  ```
  InvalidDiskCapacity = "InvalidDiskCapacity"
  FreeDiskSpaceFailed = "FreeDiskSpaceFailed"
  ```

### Probe Events

  ```
  ContainerUnhealthy    = "Unhealthy"
  ContainerProbeWarning = "ProbeWarning"
  ```

### Pod worker Events

  ```
  FailedSync = "FailedSync"
  ```

### Config Events

  ```
  FailedValidation = "FailedValidation"
  ```

### Lifecycle hooks

  ```
  FailedPostStartHook = "FailedPostStartHook"
  FailedPreStopHook   = "FailedPreStopHook"
  ```
