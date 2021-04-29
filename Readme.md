<!--
  Title: Navigation architecure
  Description: Stop reloading previous fragment by using Navigation architecure,
  How to prevent previous fragment to show up after pressing back button using navigation controller?.
  Author: Amit Rawat
  -->
  
  1.Stop reloading previous fragment by using Navigation architecure
  2.Navigation Architecture Fragment Reload Problem solved .


Ex. As if we are moving from List-fragment to back on userDetail Fragment on back pressed no need to reload List-fragment again by using Android Jet Pack and Navigation Architecture

```<fragment
     <fragment
        android:id="@+id/my_nav_host_fragment"
        android:name="androidx.navigation.fragment.NavHostFragment"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:defaultNavHost="true"
        app:navGraph="@navigation/navigation_graph" />
        
