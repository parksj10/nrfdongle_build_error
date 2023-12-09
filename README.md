# nRF Connect SDK MCU Boot build error for dongle

## Initialization

```shell
west update
```

### Building and running

Successful build command:

```shell
west build -b nrf52840dk_nrf52840 app --pristine
```

erroring build

```shell
west build -b nrf52840dongle_nrf52840 app --pristine
```