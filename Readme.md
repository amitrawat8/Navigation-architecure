Stop reloading previous fragment by using Navigation architecure


Ex. As if we are moving from List-fragment to back on userDetail Fragment on back pressed no need to reload List-fragment again by using Android Jet Pack and Navigation Architecture

'<fragment
        android:id="@+id/my_nav_host_fragment"
        android:name="androidx.navigation.fragment.NavHostFragment"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:defaultNavHost="true"
        app:navGraph="@navigation/navigation_graph" />'
