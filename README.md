//# GunFireScript
//GunFire script for Unity 3D
function Update () {
  if(Input.GetButtonDown("Fire1")){
    var mygunsound : AudioSource = GetComponent.<AudioSource>();
    gunsound.Play();
    GetComponent.<Animation>().Play("GunShot");
   }
  }
