using System;
using System.Collections.Generic;
using System.Linq;
using System.Web;
using System.Web.Http;
using System.Web.Mvc;

namespace EasyAuthAPIPOC.Controllers
{
    public class RFPController : ApiController
    {
        public IEnumerable<RFP> Get()
        {
            return new List<RFP>()
            {
                new RFP()
                {
                    ID = "407QFS",
                    Name = "Cloud Modernization",
                    Description = "Cloud Modernization"
                }
            };
        }

        // GET api/values/5
        public string Get(int id)
        {
            return "value";
        }
    }

    public class RFP
    {
        public string Name { get; set; }
        public string Description { get; set; }
        
        public string ID { get; set; }
    }
}
