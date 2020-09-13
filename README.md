# prokura-drone
prokura-drone is a API that controls drone using mavlink message running on top of Ardupilot or PX4. 

## Mission format for both sending and receiving mission
```
	{
  name: 'asasas',
  radius: '20',
  speed: '20',
  home: 'Biratanagr',
  destination: '5f2bb9d7e0d78272f38eb279',
  waypoints: [
    {
      altitude: 0,
      radius: 0,
      action: 'takeoff',
      lat: 26.818175084140602,
      lng: 87.28325418453437
    },
    {
      altitude: '20',
      radius: '20',
      action: 'waypoint',
      lat: 26.817065334581564,
      lng: 87.28149404510873
    },
    {
      altitude: 0,
      radius: 0,
      action: 'land',
      lat: 26.817773279520665,
      lng: 87.27882163829784
    }
  ]
}
```
Also, Can read mission stored in txt file. 
