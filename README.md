# NSL_23-24_PayloadEECS 🚀

![GitHub top language](https://img.shields.io/github/languages/top/usfsoar/NSL_23-24_PayloadEECS.svg)
![GitHub contributors](https://img.shields.io/github/contributors/usfsoar/NSL_23-24_PayloadEECS.svg)
![GitHub issues](https://img.shields.io/github/issues/usfsoar/NSL_23-24_PayloadEECS.svg)

![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)

![Payload BAnner Image](Banner.gif)

## For new members
Hello and welcome to SOAR's Payload EECS repository. Please feel free to take on any issue on the [issues tab](/issues), and if you want to contribute your solution there are currently 2 approaches:
1. **Forking our repo**: This is the easiest way to get started, no permissions required. Watch [this video](https://youtu.be/uhwIgnRaXew)
2. **Creating a branch as a member**: This way requires you to be added to one of our teams to even make a pull request, so if you're not sure aobut staying long term I'd suggest going with *forking*, but if you're commited to helping us out here is what you can do:
> 1. Ask one of the leads to add you to a team as a contributor
> 2. Download [Github Desktop](https://desktop.github.com/) and set it up to your github account
> 3. Open Github Desktop then click on `File > Clone Repository` Then switcht to the tab `URL` and paste our repo link: `https://github.com/usfsoar/NSL_23-24_PayloadEECS`
> 4. Once cloned and in your computer you are ready for your first contribution
> 5. Pick an issue from the [issues tab](/issues) and assign yourself to it
> 6. On Github desktop click on `Branch` then a list of branches will appear, click on the butotn `New Branch`. Name the branch as something related to the issue you will be taking, I'd suggest `issue/47-fixing-bluetooth` for example
> 7. Modify the code as you see fit to solve the issue you chose.
> 8. Once your code is ready commit, push and publish your branch,and then head over to the [Pull Requests tab](/pulls)
> 9. Create a pull request and make sure to specify your branch as the `compare`
> 10. Write a short description on the changes you did and if you want add @L42ARO as a reviewer
> 11. Create the pull request and if the changes don't break anything it should be added

Either approach you take, you're gaining some valuable `git` skills, furthermore you can make as much mistakes as needed, it's part of learning! And you won't have to fear "breaking something important".

### Some tips on picking up Issues
- Any issue with the label `Good First Issue` is probably an easy issue to start with and it might have a guided solution to follow
- Some issues may say **Blocked by** and then list another issue, this just means you most likely need to solve that other issue first or wait for someone else to solve it before proceeding
- Issues should be labeled with the programming language required so you can pick and choose what you're most comfortable

## For leads

1. Clone this repo on your computer
2. If you take on an issue create a branch to work on that issue. Name it however you want or if you want name it like `issue/46-fix-this-thing`
3. Once your code is complete create a pull request referencing your branch
4. Explain a little why you're making the change you're making
5. Wait for another lead to verify it and it'll get merged

## Resources

- [ESP32S3 Docs](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/#hardware-overview)
- [BNO055 IMU Docs](https://learn.adafruit.com/adafruit-bno055-absolute-orientation-sensor/arduino-code)
- [BMP390 Baromter Docs](https://learn.adafruit.com/adafruit-bmp388-bmp390-bmp3xx/arduino)
- [900 Mhz Lora docs](https://reyax.com/products/rylr998/)

## Payload System

![Payload Design Image](Design/Payload_design_v3.png)
![Payload Stemnaut details](Design/Payload_stemnaut_details.png)



## Transmitters Table
Netowrk ID : 5

|    **Name**     | **Frequency**                                      | **Channel** |
| --------------- | -------------------------------------------------- | ------- |
| Deployment LoRa | 905 MHz                                            |    5    |
| Drone LoRa      | 905 MHz                                            |    10   |
| Recovery LoRa   | 442 MHz                                            |    9    |



## Viewing charts

For flowcharts and general charts we make, we use [Draw.io](https://draw.io), so just go there and import the drawio files.
