Module – Implement Ephemeral Authentication
=============================================

As organizations move towards MFA to secure their enterprise applications they often struggle ways to implement SSO.  They must make sacrifices at security because if they implement MFA at the proxy layer it allows for Single-Sign On but often requires a less secure authentication method to the resource do to the introduction of service accounts requiring password.  If an organization choses to implement MFA directly at the application, SSO it lost. 

F5's C3D allows the best of both worlds by allowing MFA at the proxy level of the organizations choosing without reducing security between the proxy and resource when it comes to SSO.


.. toctree::
   :maxdepth: 1
   :glob:

   lab*