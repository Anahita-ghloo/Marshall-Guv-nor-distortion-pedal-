# Marshall-Guv-nor-distortion-pedal-

This repository consists of schematic and PCB of Marshall Guv’nor distortion pedal for electric guitar. 
This is a self-training project.


Table of Contents
-----------------

  * [Requirements](#requirements)
  * [Schematic](#schematic)
  * [Contributing](#contributing)
  * [Support and Migration](#support-and-migration)
  * [License](#license)

Requirements
------------

The script requires the following to run:

  * Altium Designer
  * Dual up-amp IC : TL072cp
  * volume potentiometers of type A & B
  * many other electronic elements such as resistors, capacitors and ...


Schematic
-----

First you should install python on your system and download the dataset.
Then you can run the script with cmd or Anaconda Prompt.

example:
```sh
(base) C:\>python Compare_ID_Shenasa.py --index_directory C:Anahita\dataset\index --others_directory C:Anahita\dataset\others
--output_directory C:\Users\Anahita

```
Note : There is a space between each directory above.

The Script has the following inputs.

`index_directory` is the path of index folder, where the main pictures exist. 

`others_directory` is the path of others folder, where the copies of index pictures exist. 

`output_directory` is the path of output, where the two folders of "same" & "different" are created. 

### Error handling

The script will raise fallowing error if directories are not provided.

AttributeError: `NoneType` object

Contributing
-----

Not yet

Support and Migration
-----

Not yet

License
-----

Not yet
