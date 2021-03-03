# Distribution
IDD Releases for `Debian/Ubuntu`, `macOS`, and `Windows`.

## Download Latest Releases

### Debian/Ubuntu

```bash
curl -s https://api.github.com/repos/whitehatsec-innovations/distribution/releases/latest \
| grep "browser_download_url.*deb" \
| cut -d '"' -f 4 \
| wget -qi -
