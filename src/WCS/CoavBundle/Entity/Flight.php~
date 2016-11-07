<?php

namespace WCS\CoavBundle\Entity;

use Doctrine\ORM\Mapping as ORM;

/**
 * Flight
 */
class Flight
{
    /**
     * @var int
     */
    private $id;

    /**
     * @var string
     */
    private $departure;

    /**
     * @var string
     */
    private $plane;


    /**
     * @var string
     */
    private $arrival;

    /**
     * @var string
     */
    private $pilot;

    /**
     * @var int
     */
    private $freeSeats;

    /**
     * @var \DateTime
     */
    private $takeofTime;


    /**
     * Get id
     *
     * @return integer 
     */
    public function getId()
    {
        return $this->id;
    }

    /**
     * Set departure
     *
     * @param string $departure
     * @return Flight
     */

    /**
     * Set plane
     *
     * @param string $plane
     * @return PlaneModel
     */

    public function setDeparture($departure)
    {
        $this->departure = $departure;

        return $this;
    }

    /**
     * Get departure
     *
     * @return string 
     */
    public function getDeparture()
    {
        return $this->departure;
    }

    /**
     * Get plane
     *
     * @return string
     */
    public function getPlane()
    {
        return $this->plane;
    }

    /**
     * Set arrival
     *
     * @param string $arrival
     * @return Flight
     */
    public function setArrival($arrival)
    {
        $this->arrival = $arrival;

        return $this;
    }

    /**
     * Get arrival
     *
     * @return string 
     */
    public function getArrival()
    {
        return $this->arrival;
    }

    /**
     * Set pilot
     *
     * @param string $pilot
     * @return Flight
     */
    public function setPilot($pilot)
    {
        $this->pilot = $pilot;

        return $this;
    }

    /**
     * Get pilot
     *
     * @return string 
     */
    public function getPilot()
    {
        return $this->pilot;
    }

    /**
     * Set freeSeats
     *
     * @param integer $freeSeats
     * @return Flight
     */
    public function setFreeSeats($freeSeats)
    {
        $this->freeSeats = $freeSeats;

        return $this;
    }

    /**
     * Get freeSeats
     *
     * @return integer 
     */
    public function getFreeSeats()
    {
        return $this->freeSeats;
    }

    /**
     * Set takeofTime
     *
     * @param \DateTime $takeofTime
     * @return Flight
     */
    public function setTakeofTime($takeofTime)
    {
        $this->takeofTime = $takeofTime;

        return $this;
    }

    /**
     * Get takeofTime
     *
     * @return \DateTime 
     */
    public function getTakeofTime()
    {
        return $this->takeofTime;
    }

    /**
     * Set plane
     *
     * @param \WCS\CoavBundle\Entity\PlaneModel $plane
     * @return Flight
     */
    public function setPlane(\WCS\CoavBundle\Entity\PlaneModel $plane = null)
    {
        $this->plane = $plane;

        return $this;
    }
    /**
     * @var \WCS\CoavBundle\Entity\Terrain
     */
    private $departures;

    /**
     * @var \WCS\CoavBundle\Entity\Terrain
     */
    private $arrivals;


    /**
     * Set departures
     *
     * @param \WCS\CoavBundle\Entity\Terrain $departures
     * @return Flight
     */
    public function setDepartures(\WCS\CoavBundle\Entity\Terrain $departures = null)
    {
        $this->departures = $departures;

        return $this;
    }

    /**
     * Get departures
     *
     * @return \WCS\CoavBundle\Entity\Terrain 
     */
    public function getDepartures()
    {
        return $this->departures;
    }

    /**
     * Set arrivals
     *
     * @param \WCS\CoavBundle\Entity\Terrain $arrivals
     * @return Flight
     */
    public function setArrivals(\WCS\CoavBundle\Entity\Terrain $arrivals = null)
    {
        $this->arrivals = $arrivals;

        return $this;
    }

    /**
     * Get arrivals
     *
     * @return \WCS\CoavBundle\Entity\Terrain 
     */
    public function getArrivals()
    {
        return $this->arrivals;
    }
}
