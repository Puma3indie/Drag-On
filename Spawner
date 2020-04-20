using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Spawner : MonoBehaviour
{
    public float curr;
    public GameObject enemy;
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        if(curr <= 0)
        {
            curr = 10;
            Instantiate(enemy, transform.position, transform.rotation);
        }
        curr -= Time.deltaTime;
    }
}
