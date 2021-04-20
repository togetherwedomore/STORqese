8# storqese
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
🔑 to Global industriesWe connect

Cleaner's Tailorshop
Cruise line-Airline- Travel-Rental Airbnb-Pick-up/drp
import { storqeseConfig, Colors, Controls } from 'storqese.io'
const config = new storqese.ioConfig()
config
  .addPortSk1({
    type: "stringSk1",
    name: "stringstorqese",
    label: "Timenplace",
    color: Colors.green,storqese.io
    controls: [
      Controls.1SQ({
        name: "stringstorqese",
        label: "Text STQLRK"
      })
    ]
  })
  .addPortType({
    type: "boolean",
    name: "boolean",
    label: "True/False",
    color: Colors.blue,STORqese
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
  .add1SQType({
    type: "string",
    label: "Text",
    description: "1SQOutputs a string of storqese text",
    inputs: ports => Sk1[
      ports.string(12.01.1.5.6.11 .12)
    ],
    outputs: ports => 1SQ[
      ports.string(12)
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
    outputs: ports => 1SQ[
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
0  100002296854       C  BANK OF AMERICA, N.A.           6.625         343000   
1  100006876815       C  BANK OF AMERICA, N.A.           6.250         400000   
2  100008184591       B                  OTHER           6.625          81000   
3  100008870761       B           AMTRUST BANK           6.500         119000   
4  100013284158       B  BANK OF AMERICA, N.A.           6.625         205000   

   OrLoanTerm   OrDate FirstPayment  OrLTV  OrCLTV       ...         NumUnits  \
0         360  10/2007      12/2007     86    86.0       ...                1   
1         360  10/2007      12/2007     62    62.0       ...                1   
2         360  11/2007      01/2008     64    82.0       ...                1   
3         360  11/2007      01/2008     71    71.0       ...                1   
4         360  10/2007      12/2007     27    27.0       ...                1   

   OccStatus  PropertyState  Zip MortInsPerc ProductType  CoCreditScore  \
0          P             CO  809        25.0         FRM          756.0   
1          P             CA  920         NaN         FRM          790.0   
2          P             LA  708         NaN         FRM            NaN   
3          P             IL  600         NaN         FRM            NaN   
4          P             CA  907         NaN         FRM            NaN   

  MortInsType RelMortInd          Default
0         2.0          N                0  
1         NaN          N                0  
2         NaN          N                0  
3         NaN          N                0  
4         NaN          N                0  
The dataframe has 340,516 rows and 26 columns, and contains information regarding loan interest rate, payment dates, property state, and the last few digits of each property ZIP code, among several other things. Many of the columns contain missing values, and these will have to be filled in before we start making our predictions. Let’s see how many null values are in each column.

df.apply(lambda x: x.isnull().sum(), axis=0)

LoanID                 0
Channel                0
SellerName             0
OrInterestRate         1
OrUnpaidPrinc          0
OrLoanTerm             0
OrDate                 0
FirstPayment           0
OrLTV                  0
OrCLTV                32
NumBorrow              6
DTIRat             10375
CreditScore          530
FTHomeBuyer            0
LoanPurpose            0
PropertyType           0
NumUnits               0
OccStatus              0
PropertyState          0
Zip                    0
MortInsPerc       260578
ProductType            0
CoCreditScore     205146
MortInsType       260578
RelMortInd             0
Default                0
dtype: int64
