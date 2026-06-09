
# Release Notes for <mark>STM32U5G9J-DK2 BSP Drivers</mark>
Copyright &copy; 2023 STMicroelectronics\
    
[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com)

# Purpose

These drivers provide a set of functions to manage:

- LEDs, push-button, and COM ports
- OctoSPI NOR Flash memory
- HexaSPI PSRAM memory
- LCD
- Touch Screen

*Note that stm32u5g9j_discovery_conf_template.h file must be copied in user application as
stm32u5g9j_discovery_conf.h with optional configuration update.*


# Update history

<label for="collapse-section4" checked aria-hidden="true">__V1.2.1 / 11-May-2026__</label>
<div>			

## Main changes

- Remove incorrect references to non-U5 boards.
- Fix Misra-C 2012 Rule 2.2_c violation.


## Dependencies

This software release is compatible with:

-   BSP common drivers __V7.2.1__ or above

## Limitations

- Multitcouch functionality not supported

</div>

<label for="collapse-section3" checked aria-hidden="true">__V1.2.0 / 13-February-2024__</label>
<div>			

## Main changes

- Add PWM backlight control in **stm32u5g9j_discovery_lcd** drivers
- STM32U5G9J-DK2_BSP_User_Manual.chm: Updated


## Dependencies

This software release is compatible with:

-   BSP common drivers __V7.2.1__ or above

## Limitations

- Multitcouch functionality not supported

</div>

<label for="collapse-section2" checked aria-hidden="true">__V1.1.0 / 20-October-2023__</label>
<div>			

## Main changes

- MCUAstyle coding rules compliance Formatting
- STM32U5G9J-DK2_BSP_User_Manual.chm: Updated


## Dependencies

This software release is compatible with:

-   BSP common drivers __V7.2.1__ or above

## Limitations

- Multitcouch functionality not supported

</div>


<label for="collapse-section1" checked aria-hidden="true">__V1.0.0 / 07-June-2023__</label>
<div>			

## Main changes

- First official release of __STM32U5G9J-DK2__ BSP drivers in line with STM32Cube BSP drivers development guidelines (UM2298)

## Dependencies

This software release is compatible with:

-   BSP common drivers __V7.2.1__ or above

## Limitations

- Multitcouch functionality not supported

</div>


For complete documentation on <mark>STM32 Microcontrollers</mark> ,
visit: [[www.st.com](http://www.st.com/STM32