# Export-Layer-Coordinates
This is useful when you need to generate exact locations for touch-points over an image and don't want to manually measure each location.

#### Installation
1. Place script in:
       <br/>Mac: '~/Applications/Adobe Photoshop CS#/Presets/Scripts/'
       <br/>Win: 'C:\Program Files\Adobe\Adobe Photoshop CS#\Presets\Scripts\'
2. Restart Photoshop

#### Use
In a PSD:
1. Set your touch point layers. A 10x10 sphere is usually an easy way to map out your touchpoints.
2. Layer names are exported as labels in the .txt file, so rename layers as needed.
3. Choose File > Scripts > Export Layer Coordinates
4. Choose destination folder.  File exports as `FileName.psd.txt`

#### Notes
X and Y coordinates are taken from the top left of the document.
<br/>The script reads the top left bounds of every layer, so be prepared to adjust for offset if you need measurements exact down to the pixel.
