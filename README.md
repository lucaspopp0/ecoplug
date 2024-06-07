Original source: https://github.com/gbealmer/pyecoplug

# ecoplug

HACS integration for WiOn eco plugs.

## Home Assistant installation

1. Clone the repo

2. Relocate `ecoplug` to your `custom_components` directory

3. Add the following to your configuration:
    ```yml
    switch:
      - platform: ecoplug
        scan_interval: 10
    ```

4. Restart home assistant
