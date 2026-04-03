# InMusic Rockchip CI

CI/CD repository for building RK7 Rockchip Linux images.

## Supported Boards
- AZ04B
- AZ07

## Build Type
- Validation build

## How to Trigger Build
GitHub Actions -> Build -> Select Board

## Outputs
- Compressed Rockchip `raw.img` artifact (`.img.xz`)

## Required Repository Secret
- `GITLAB_TOKEN`
  - Used to access `code.focalcrest.com` during the Buildroot build
