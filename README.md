# Snap-LeakIP

SnapIPLeak is a script to capture and leak a victim's IP address through a Snapchat call using ARP spoofing and packet analysis.

## Important Notes
For those of you who are having trouble: please, **you must call the victim exactly when the script asks you to**, not before and not after, **_because the IP leaks in the first few seconds of the call_**. If you call before executing the script or after it tells you to call, it won’t work.

## Usage
Just run the script and follow the instructions. You only need to call the victim and wait for about 5 seconds to capture their public IP address.
- `sudo ./SnapLeakIP.sh`

## Installation
- `git clone https://github.com/CykH4ck/Snap-LeakIP/`
- `cd SnapIPLeak`
- `chmod +x SnapLeakIP.sh`
