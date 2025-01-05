# CAPI-Direct
Oculus CAPI-like SDK which lets you use Oculus headsets directly without the Oculus runtime, powered by OVRSDK.

# Info about rendering/compositing
CAPI-Direct does not contain any functions used to submit frames to a compositor, as CAPI-Direct does not contain a compositor, and is intended for integration into other VR runtimes or software which needs direct access to Oculus hardware, without running the Oculus runtime.

An example of such implementation can be seen with OculusWRP, which uses CAPI-Direct to allow Oculus headsets to run natively under SteamVR.
