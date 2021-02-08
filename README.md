# storqese
cuddly-octo-funicular||baby-diners|8-portals|fam-trvl
response keys for securely ordering and operating all 
shipper keys 
retail and service activities. These include the ship's
 store(keys), 
vindur key bending machines, video(Key)games,smartshops,
clikey kiosks, 
Cleaners and tailor shops. Travel,Cruise Upscale
creature comforts and services cared for, 
which is a significant factor in overall decentralizing
🔑 to Global industries
We connect
 Cleaner's Tailorshop
Cruise line-Airline- Travel-Rental Airbnb-Pick-up/drp
import { FlumeConfig, Colors, Controls } from 'flume'

const config = new FlumeConfig()
config
  .addPortType({
    type: "string",
    name: "string",
    label: "Text",
    color: Colors.green,
    controls: [
      Controls.text({
        name: "string",
        label: "Text"
      })
    ]
  })
  .addPortType({
    type: "boolean",
    name: "boolean",
    label: "True/False",
    color: Colors.blue,
    controls: [
      Controls.checkbox({
        name: "boolean",
        label: "True/False"
      })
    ]
  })
  .addPortType({
    type: "number",
    name: "number",
    label: "Number",
    color: Colors.red,
    controls: [
      Controls.number({
        name: "number",
        label: "Number"
      })
    ]
  })
  .addNodeType({
    type: "string",
    label: "Text",
    description: "Outputs a string of text",
    inputs: ports => [
      ports.string()
    ],
    outputs: ports => [
      ports.string()
    ]
  })
  .addNodeType({
    type: "boolean",
    label: "True/False",
    description: "Outputs a true/false value",
    initialWidth: 140,
    inputs: ports => [
      ports.boolean()
    ],
    outputs: ports => [
      ports.boolean()
    ]
  })
  .addNodeType({
    type: "number",
    label: "Number",
    description: "Outputs a numeric value",
    initialWidth: 160,
    inputs: ports => [
      ports.number()
    ],
    outputs: ports => [
      ports.number()
    ]
  })
